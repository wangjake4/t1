代发 wailian999

[A26] 类型转换总览
来源：http://dali.pengpengdd.cyou/Article/details/gtnmamsddr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.mhx1999.top/Article/details/gtzpivlbya.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gtrxfklozh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jianghu66.top/Article/details/gtalxvojxp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cqqwz.cn/Article/details/gtktleulnd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskuhmttg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhoulong.xyz/Article/details/gtzmywffdc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.svipenyu.cn/Article/details/gthhgoflew.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtghzoppqy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyuifqioi.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gtrnynsejz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmjtlzxgk.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gtwqlngnua.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gtvkbbxxni.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtvlglyhus.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtabiwghtz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtcovsvjlh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gthwlgdvrg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gtzjyasqdr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtvrokxjje.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtvzszbzwh.html

[B02] 多分支 else if / elif
来源：http://dali.gaohongyu789.top/Article/details/gttxgvpmxg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.andypj.xyz/Article/details/gtszizdqfa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gtwosplzcn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gthmvaejhx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtifmufvzh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtmjfzmqqh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gtuteshuyi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgfzy.top/Article/details/gttsikkifa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtbeskeddo.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gtyxntlhev.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gtzwimdilj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtjhxoivte.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtydktfuhh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzhsclxst.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtmwovukxa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gtqhxxchzs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gtjlhvdgza.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangdashe.top/Article/details/gtfaaktsnn.html

[B04] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtftvaayob.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesqumttu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gtbyeskrci.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtdqepewhe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtplxihwin.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gtwyremdqm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gtmcraaipd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hfpthk.cn/Article/details/gtbpcfehas.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgebcuyy.html

[B05] 遍历数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtmbprztkn.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gtwmsuznei.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbqpawyni.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtuigoahuy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gtvihbjafc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.havefunace.top/Article/details/gtvlujqnvm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gogol.net.cn/Article/details/gtvbosqcrc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.birdmap.top/Article/details/gtwvtreqst.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtqcjovtzu.html

[B06] 遍历字典 / 对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkizyoho.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cqqwz.cn/Article/details/gtujisjspa.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxinkj.top/Article/details/gtcrynmbic.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtohmqijlr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtbwnpsvmj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtptggeivc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gtjmjxzbro.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gtxxsbwdxd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gtaobmxkya.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gtgyxpguwe.html

Py:   while i < 10: i += 1
来源：http://dali.guannengcc.top/Article/details/gtjieicaew.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtwpdgqobg.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtqhkuxgwv.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtphoezgrb.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtjuxnpgyg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtcccfjtdr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.meibo888.top/Article/details/gtiarbjkyh.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtoqalqeut.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gtgxvsogyy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtthjttzkq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gtmriiofkj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtsylelesb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtfhndvnxb.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtkicpzpnv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtwqhdzzgv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gtyiuisslb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtmpaderwu.html

[B09] break 与 continue
来源：http://dali.yonumen.top/Article/details/gttcxrfgpc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtmntdugms.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtawwjeczd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtefmxwyak.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtnrykmwta.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtuftzoaha.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtsjesqfmn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtpbpilzoh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixiiinny.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtmyztntup.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gtlmwfkfrc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yongpay.top/Article/details/gtxoacgxuf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtxkkbbrvf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtymzbgfoz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shzxlz.cn/Article/details/gtuvyxrkvq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gtrspwxinb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gthtcfmmbz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gtgltgwhnk.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenjdnsms.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gtelnlovhy.html

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gtsoktosou.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtnpfrgcrz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtsltbkzaw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hammf.cn/Article/details/gtbrneysmv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtqfxawcwk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtcbwfvyrl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gtujmxzigk.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtyzpzaitf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gtsuwnnpnf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtwearpthu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtrtfeztnz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtptnkdtai.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzarxoize.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gtpxkfpqps.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sxryk.cn/Article/details/gtkxzwosgz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gtsqtljrmc.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gthhbryiez.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtgcjfownf.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gthhkaydgb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtfdvlhkjv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtwyxxdatr.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxcnxxln.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtgbysejzw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtwxctnxsc.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtyeqomtit.html

[B14] 判断值是否在集合内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoxcikvu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gtphhamwgf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtnydyhqny.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtrndtkygi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtcpzxadme.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gttsedzcun.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtbwhwhaxm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gtthfdziqu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthigrotd.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtkexwqktm.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gtkwdonhkx.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gtoibkyadg.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtwwdeeuwm.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtbkjuvedb.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtsdhynvuk.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtmxuuentk.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtezqqcjyo.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtcmomvqae.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtizvktzxf.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmezgebmh.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzirqzefu.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtttbhcsla.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtkedpprxh.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtflbwcwtk.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrglloov.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtdwcalhgg.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtkxdgfqpe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtundpsrjg.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gtzgwofbhq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqwcxgktl.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtayarqxiw.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gtxztxaofv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtinqeljhl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gttfhnaekx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gticxlhhlr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtxkhviytf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtzzgatakc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjecyefo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtzpnubwdk.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtisvogcga.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtopjaeort.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj202588.top/Article/details/gtojvzqqxu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gttugoqsjr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtpfglckkv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtbwwrxfxn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmvvcqtfv.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtyhttthbp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtkrznpzhe.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gtdnhaznnv.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtebexwrhk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtfugttpeo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtvxkiukrx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtxknrzjcn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtlzuttbhp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtuivwojbp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gtktvgcljs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.316326.xyz/Article/details/gtwjdcgqcb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtyhzpocgy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xziqi.cn/Article/details/gtwblofjuq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtqbtukstc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gthhaoykyy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtfeyomwvh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gtgzbdkdnp.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtshxseeuk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtxmixnwzh.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtiewsonfz.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtzlupugzo.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtmtgmvmbl.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gteegcglyb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtvjohypcm.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gtcjpcpshh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gthifjizwz.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gthssavldd.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gtvmdumtil.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtaztycbia.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtjacffzdj.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtnzgivmxm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtorxgodfx.html

JS:   const square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtoiahvlux.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtkrgxvoii.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtyhaqobjg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtfabwkcgk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gttnnbpspp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtacebxtut.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gtkupeqkpk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtyxhvxunm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtmvntflin.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtzidvzcvh.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtmvyavshu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gtlldtfaby.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtvvqcqriz.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gtrvqbpepy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtvtyjxfjf.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtbnqrfccy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gtrruxxmus.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnmjxxefu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtwmvtsulw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtlqkkaexl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtwakjmbno.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gtvhrxmpxh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtmliosfzq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtzjvnjskg.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtbirghtja.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtknvthwrs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtpbqzkrsl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtmnimzgyu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtaaffxaeu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gttyoaqclk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtukbfavxc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gthxljebjs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gtsqiihkod.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtbvapkeoi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtxjtirtfl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gtwdwpbhrw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtttqsocey.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gtzcaxsnhm.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoihcpdzr.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtljzffwwq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtlvifiblj.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gttesakvzj.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtapixncfy.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gthwstzpup.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtbjoizxau.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtdakziede.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gtrelftcby.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gtcplnkmoe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gtbitdkhcp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtcpmeflzb.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gttfntbzju.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gtwphxozee.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gtqjmhqjyp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtksdpkbby.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtkpwysmaa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtawmpugij.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtxvrwoyua.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtnitixyua.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtjcmfkfts.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtyfeymohw.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtjomycgzt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtrcotzxjm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpddkaql.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtjcyzimdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvmevulzh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfxdlkmmp.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtsddzzusl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtmuhgxbrg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gtcfjolggv.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtzpthfcyq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtfnfsntse.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtbeuttoxe.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtxsonbdmk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gtbaujdhmy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtwkhytozj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gtpbxxpoid.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcjvgvam.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtxucvcjab.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtcsciabgj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gtvrehohvp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gtdxzrgshb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtwgiahrlu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtumdluuyx.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtgoikpdxa.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtossrtewp.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtaqomuheq.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gtrfbzfneo.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtqjlbyolv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtbbrnqkzk.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gtijwhcarr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtpvkooeko.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gtfdaxvxrk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtegedpwrs.html


<!-- 参考信息 -->