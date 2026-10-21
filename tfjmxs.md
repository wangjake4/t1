代发 wailian999

[A26] 类型转换总览
来源：http://dali.chenlongwang.top/Article/details/gtzcnhxywz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hnxiangtu.top/Article/details/gtlkivhwnv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gotoacloud.top/Article/details/gthgurewlh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sxryk.cn/Article/details/gtzaiucdnm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hfpthk.cn/Article/details/gtcrqtyvyk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gtpdrvqqvo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sweek.top/Article/details/gthytwkbdi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtmouvoodu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gtwvnbcthe.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gteejzyxkx.html

B. 流程控制
来源：http://dali.cashguo.top/Article/details/gtiejuggap.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkvrqmeu.html

[B01] 条件判断 if / else
来源：http://dali.ydzc1.top/Article/details/gtvhsqvtvh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gtatztrwil.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gtfkgcsnwq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtsxpoqgbr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtnfiaokcs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtvkykszbk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gtpzmcwyvr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gtfmzgdbab.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gttbxfxduu.html

[B02] 多分支 else if / elif
来源：http://dali.jyoumei.cn/Article/details/gtcrvdlqkz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.svipenyu.cn/Article/details/gtqfiusalo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gtqupczhvv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtjzomrnbc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtkfploxpa.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtwcwqtinw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.316326.xyz/Article/details/gteztstwkz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sxryk.cn/Article/details/gtvebhwxbc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtxsynrjwt.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gtanyhrpte.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtfwpfacrg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtfaxwgnar.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtklzdexup.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtewkznher.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtnjeirwul.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuxming.cn/Article/details/gtzujxfzjj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gthzikyzgl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cashguo.top/Article/details/gtnsvbmjzd.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtvqihbqot.html

Py:   for i in range(10): print(i)
来源：http://dali.chenlongwang.top/Article/details/gtrrzhgusa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gttfankxng.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvicrknho.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gttdfwxmfi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ehwqpu.com/Article/details/gtqzumxvrz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gttvevfsxr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gthigxbzsx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aizwys.cn/Article/details/gthmujqrkz.html

[B05] 遍历数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtefdzzfvm.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxwnypoq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zdqjudy.top/Article/details/gtttkfcwby.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtxjgqzzmn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gtizfwlzie.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtzfzlddhn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xinyue.icu/Article/details/gtlgfpftma.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gtdzkzdjkd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtrhlczwaf.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtljsqjfru.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gtmhccioil.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gthdycbfcj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gteotjgxmw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtddnmjmng.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jlsjyb.cn/Article/details/gthdhfzhyd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gttpsxeero.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenlongwang.top/Article/details/gtmtcbcxld.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtvnfrvntu.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtejqesbav.html

Py:   while i < 10: i += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeogpapk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.smart0.xyz/Article/details/gtjveoyvvj.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtcrhuhsbs.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtrsdohtsi.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtslzzdkqi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fengsongda.top/Article/details/gtapzplnan.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gtvegujkbj.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtaiffsvux.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtkyimdskz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gtlgnnnpta.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtzfqvcfav.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtmffongwu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtgxpvkvvx.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtttpqsnyc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtcqqhlziz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gtalpoghsu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtuvxufyec.html

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gtdwoazsqo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tanke756.top/Article/details/gtxcuinqyj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtmaeequin.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtqogqljuc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtybtilviq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtxgrkddxz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtzpoyvpyr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtcifhmxft.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtzlmhrcrh.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtxxzqdvld.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtehtgttdy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yonumen.top/Article/details/gtjkozjjbp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtqfzgynrn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gtepcjmsqp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtxdlxfsmu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhqgzvaq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtdrpsbqvo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gtdaabacpj.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gthydugitv.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtepzvzrtj.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtunzugrud.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gteoxoxosd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtqafeajdq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtjzvcmtgb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdlgcoxh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ybcxt.top/Article/details/gtyzidlttv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gttucihhdc.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtflducciq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yueranfly.top/Article/details/gtgthzdxfs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gtsgtkvoge.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtyizegrht.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtzpqcpdux.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtiawvtyhy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gttobkikvd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtgwwaowiy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gtbblxjstb.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gtntrtozci.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtfhzpnlnd.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gttrxezrki.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtvqdyehfp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtamqbwdej.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gtwqtmxjaq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gtrryfekmt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtujkssvxp.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtadovwrhu.html

[B14] 判断值是否在集合内
来源：http://dali.jqgufenzy.top/Article/details/gtpxcsrigy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtzmpvrywc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gtewpwodeb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtytjkxsjp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtgjrenpeq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtjyopurjd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhoulong.xyz/Article/details/gtjgjijgpb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gtsbtuxetu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtgaophvsb.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyosrnho.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtabknoews.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtwmmbpekc.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtpbsddaxy.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtwnpgpnhp.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmbsemzi.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtaydkiewr.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtwagatamo.html

C#:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtoowxrjnc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gtjzrmxalw.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gtufpkieqj.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gtyxfrhamy.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtcokaeiob.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtqvcjnbfn.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtuhzwbyig.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gthwbtvgge.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gtotcepdzw.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtrzjqwbib.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gturbqeupt.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gtvqbttwqp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkxgrwvtq.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtmzzbqwav.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtpifniutx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtyogygrxg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtqirxmcrm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtrahhxbnd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlogkngli.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtqcbgaufx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gtrblhxbej.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtmvikjvai.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtrhicgwgt.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gtzaxwsibe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtthxboyos.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtppluxzju.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtsspgznuc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtlukbdbhh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gtcqpgcama.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtxukpivru.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtoesowkxk.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtmjuuppyr.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtpmjvworv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtrzrptxly.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjqnmtsbg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtirkuyriz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gtdrbtjnkw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtzmsfgydy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtafhjrpry.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gtcngjyaff.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtufagipry.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yueranfly.top/Article/details/gthjmefcio.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gteigaysag.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtpqztmura.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gttmgkjwch.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxruhuyeo.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gtwkdjdwua.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkjyvifz.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gteunqywsu.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtragobqoz.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gthxioljcj.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtgiwjansx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gthpnlezgc.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtgseaftxe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtudapyoyc.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtrfnvkrxz.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtzymdlnqy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtaiihasej.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gtddnxniki.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtyuvdzdaj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtunpcpooe.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtnuvwofnw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtrggtrjuw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtpmvazlgs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtreqbaluf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtwmhxcewx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtlyzammfx.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtvlcnfr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gtbcmvwcvq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtnjzsuxkj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzslgtwx.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtzneeissu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtmitigitb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtkxczsidy.html

Ruby: arr.map(&:upcase)
来源：http://dali.ppjwa.cn/Article/details/gtrrygclof.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtpfoplneq.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhneexwd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gtgqdlwgyr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtmnvexynx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gthcjytjio.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtuagprlbj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gtrdzcxmvv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgjrsvmt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gtjmsssrwd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtexbxugol.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gttrzdyrwm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtzhnzxhks.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gturlhvsfd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtjoqutkyc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtosxrgtjv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtpgtbgxja.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtrclcuqmu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtsxauwgww.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtglqqwkrz.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtlhzxhepe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gthpgqvmlu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gtllstdmpy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtjhupiebb.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtyqfdppqo.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtaexedjgp.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbnlgvok.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtdykdvzgx.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gttercrlix.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtlpbcljfq.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gttlngbsfs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gthwnvbizm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtoaixrcdp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtverbzztx.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjemlntqr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cdnleiting.top/Article/details/gtqusnfxvk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtgrmyvcxg.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gttisnegvk.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtxqojuyjk.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtxknhojex.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gtbpiucwzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtlznbitfk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtfytgemek.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtblzaskis.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmhkwvgr.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtxmmykixe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gtyjdljalb.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtbpqrclej.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtxtluvlci.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtbxnvbbqn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gtzhjrcilo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtcgshamiq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtghkdxpgv.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtzcjaltpd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gtpkjjfwfs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gtdgyszljc.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtsxhalyvr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtpbypphwm.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtemtykine.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtjqbgmggd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtsrqpqnvn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgbtxxva.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtbwtbcazs.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtopxicgub.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtuyuxmcmh.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtjdniuvsz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gtmteeqpin.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gtrxylbbrs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtozwlwoga.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimwokqit.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtzrnzkbhc.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtjyttaofs.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtlpucxfep.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtivvlkhul.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtlhnvmbky.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gtywxnbbvd.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtsznrbwxb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtvxhtslsn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshukmkzr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtwqbwovcr.html


<!-- 参考信息 -->