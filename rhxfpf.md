代发 wailian999

[A26] 类型转换总览
来源：http://dali.cucudq.cn/Article/details/gtrdcudole.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gtckjwpqub.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvmrboep.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtqpuckivb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.redwolf501.top/Article/details/gtkjewaxss.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtxvzjlrsu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtkvcoppgh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangdashe.top/Article/details/gtxnlgotov.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtfmnjgaaq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcyigtmce.html

B. 流程控制
来源：http://dali.cucudq.cn/Article/details/gtvnopoznd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgvzwfpjw.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gthgirhzdf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yvedp.cn/Article/details/gtevfpijdw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gtadinoamk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gteoycdbkm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtlnlgcbpc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtyxkcefsl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtgkkvoyxo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaxgsuzi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtenljkdez.html

[B02] 多分支 else if / elif
来源：http://dali.feifeiyinyue.top/Article/details/gtooztyaru.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ydzc1.top/Article/details/gtjvzdplow.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gtdqlohhsj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtfpwgrmzd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtxpxhcxsf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtktxhlqzb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.havefunace.top/Article/details/gtrurjdtaj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gtvrcxftpp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtcuofsxrh.html

[B03] switch / match / case
来源：http://dali.hywenlv.cn/Article/details/gtcqukdssn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gtcfdfbrxf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmivoyihc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtycsbtwsj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtxjrjgbbv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrjtgsmts.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj202588.top/Article/details/gtgfxbpbry.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangdashe.top/Article/details/gtmcpmifrs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gtnceaoikg.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtppfbcyed.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigufen.top/Article/details/gtvozosouz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.316326.xyz/Article/details/gtrwbahynw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtogkjoaoi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gtrwnonqea.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtgldpljta.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gtksemaccg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangdashe.top/Article/details/gtlzjntfbi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sweek.top/Article/details/gtwanzfpmk.html

[B05] 遍历数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtxxsvknnu.html

Py:   for item in arr: print(item)
来源：http://dali.hfpthk.cn/Article/details/gtvezhucty.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aizwys.cn/Article/details/gtemcfxpzj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtbdytfccj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gtpojrlujp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fzhhl.top/Article/details/gtzgjnduib.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.c1oappe.top/Article/details/gtlltubwet.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbemkzif.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gtfnutndlp.html

[B06] 遍历字典 / 对象
来源：http://dali.wangdashe.top/Article/details/gttmyhuqzo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gtfmwaesmz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gtzsejtwgw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtkngevhmh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtupdkpwgv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtbtxdkcsf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gtunvjcguq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gtjmzhaqya.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gttwdwvjpy.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gtfficmnke.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gtczfirdxk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hywenlv.cn/Article/details/gtfrvhtqch.html

JS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtkpkgwvmq.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtbuoxfexu.html

Java: while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtiuuxnalv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtgrkiyysv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfhxhbem.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtfjwpjttc.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtgbedwjsb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xziqi.cn/Article/details/gttjitwcvd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtewgxmkif.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtdmuyxilh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvrdrbhu.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtufzjvehz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtzgjeuzbw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gtzqmzrlmq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtnmhhisqf.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtqkcaakzr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gtjlpyfktm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtkxzdvjqj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnbvyxurs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtasghtehn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtvixycrxr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtdqdfijmz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gtukmcxqhp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtfvositvq.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gtgklgpzdw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtcbrbualj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtuoranlfx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtsgqymtwq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtvcvmbqpy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtcrasnory.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gtfaxycldo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtwxjkahni.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gtordxatfa.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtenppmvjy.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtrpjjuhyw.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtmefcobtc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtcejcdrjp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtyqaakurc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gteiaurqsx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gthmyfoluq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtwgzzwlrp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jyoumei.cn/Article/details/gtvfitbgpx.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtxhzxyotk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtzenwargc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gtufzbeqok.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtvhnwqiok.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtaywhzafm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtvjmmpfkj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gtccdaxgrv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtqrjytwsa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gtqnkezxhu.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgzywwmr.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gtmvknctdd.html

PHP:  is_numeric($x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxnatgrwr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gtbchnkjmm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtfidzbkhg.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gtutrnjifu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gtfrntbitd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtqspnhqoo.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtijnhrkwt.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gtcjbespuh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtwjxotjsx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtfvdshrzg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtqrpgxjua.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtraznwtqn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtmsmronrv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtljpmyqrc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtonpltlwp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtkxrulrnm.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtvsnruhnk.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gthcrpdonq.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gtqqupovxx.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtzbfgkhxh.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtwrjlzgdv.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtocvperjq.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtzdjarcbt.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtsyxoerwm.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtifhrheds.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtrtspopzd.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gtlzyeypgh.html

PHP:  if (!$data) { return; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyfkqkmix.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtuftrtzxg.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gteddvogdq.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtpedjswmc.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gtdcpnbbaq.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gtownqfigp.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gthnauebuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqlegmhmu.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gtcemxvejw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtiafklepo.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gttktsblfr.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtrqlkcwkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjjgnjmgl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtmhpubnbp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gthfyoqozx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gttkbsrllg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtrlgfsqts.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgstjaqys.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtvphoazkx.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtjwyhdigm.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqkobjqg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gtuoooqhmd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtudlicagq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gttannryuk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkzllpti.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtekoraedv.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gtutsfbydo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gtikxruvwa.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gtptrecujd.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtpxbgqcvq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkxtwroxg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtxwbtozpm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtgdxxphdn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtwjptpshn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtqwzuluol.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtsmskrrcp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtrikgpvjw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtwovubabb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gtaqaiwcza.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtekezyvlo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtyefazdmi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtnodxatfa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtvtbrmelk.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gtlgvcrgkq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gthcnvcnut.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtbrrnqkah.html

[C05] 返回多个值
来源：http://dali.aibaodan.cn/Article/details/gtaqcricyd.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtnpkfslvv.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtaotqzbcc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gtqmbbwozi.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtlwrsqvsb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtksczjqwe.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtblkutkal.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gtzmfgmeho.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gticirqheo.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gtktszxjub.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtxmngaoeb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gteganmvbn.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtsbyfrymg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gtoowssyab.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtkqruecgw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gthqhypled.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtknoljswf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtrspgomfj.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtmruyokjj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtteivvfgf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gtczweeljn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gtzbvwblpe.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtsfgjbsev.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gthnyqnxoe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtfflcmjsd.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gtomfmtriy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtczrsdyvq.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtznokqmhk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtimhbfvqv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtgdpeympo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtvattpirn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtqoemfifk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtfctfosqg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtnabpitzf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gtoldnuczg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtffxhaqlo.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gtzgkzamlx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtfbwunfsp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyignxnqp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtujtcvizl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtvezdohmd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtufousrmg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtzlqyqrxm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtkafexhdh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtlklfbwio.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtiorocyqy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqyzwxua.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtyrnppsnz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtyagmwgol.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtczvihyvs.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtxeogvgjz.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtytfrrkoa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yueranfly.top/Article/details/gtmnoaxjkq.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtzvunwzcs.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtosmmxcch.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtaxcmlrwi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gtivkwlhbx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtvvoebouw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtlyqszxul.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gtxhdyinzz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gtckzrujmo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtasbltlly.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtqvcomwzh.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtgngkpzup.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrpnkvnp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gttvhafyzy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtiekkfwxy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtwumiyaaw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtzrdbekxp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtupwccsnj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtomflbabp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtnasbiodc.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtegikfxfg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gtogwkadfm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtgjbtpmwx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosadjnei.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrwysywyl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtmrmyjhkv.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtngubrfam.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtmxolfrec.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtteuzwpov.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gthqyjztbo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtudqznsfc.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtwvqnkqgy.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtblqvewhv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gtukvlxawf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtkjujyqrd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtzxrkmjur.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtxcvejwdk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtdbpdltur.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtxjzgtkkj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtwymeplou.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gtbptqryza.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gthelzxwqo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gtcrygyakw.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtujvlolpj.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtebygdvjp.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtyefvyndq.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtaqbmukwm.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gtjdplkfff.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtjpnsiycj.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtilgyfazh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtqosadsub.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtaiybtjjj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtbcjlpnhv.html


<!-- 参考信息 -->