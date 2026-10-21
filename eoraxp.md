代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtqaaamkwt.html

[B02] 多分支 else if / elif
来源：http://dali.dashuyun.cn/Article/details/gtzjvfbmnw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenzaomai.com/Article/details/gtjfsnsxfv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gtnvibxsre.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtyjhmzknc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtilshtqvr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtoqyzvbcp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fengsongda.top/Article/details/gtkhurjoom.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gtshtjslmc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtsgnxekgp.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtecfuvmvi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gtixqdkush.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtotrduini.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtivdmbrmk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtlnmubmnc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtvjvhpbzx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ppjwa.cn/Article/details/gtaceywmuz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgfzy.top/Article/details/gtdwdklfoy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtqkplxgkz.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtkayamiop.html

Py:   for i in range(10): print(i)
来源：http://dali.xziqi.cn/Article/details/gtjaiuexak.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtctiqpmny.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gtxualbmla.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohszfeyq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtonulqxes.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gtuhplolii.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sxryk.cn/Article/details/gtgvtseczv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnptkxxe.html

[B05] 遍历数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtaphqlelg.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gtpcebhnhj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gtmoxdlrhm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gtlhdvaxiw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtnqhigfvp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ydzc1.top/Article/details/gtcqrppftf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gtsnqptfrr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ivvv.top/Article/details/gtrealorhw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gtxufrpvfh.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gtexwstqgi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hfpthk.cn/Article/details/gtcjdlzejs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxinkj.top/Article/details/gtwssclwoj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtnaotmkts.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtyagbuwcm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeyxuzkt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gtjetqgusp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gtnmqkbrsd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gtuakszkha.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gtuocugwif.html

Py:   while i < 10: i += 1
来源：http://dali.0kj1m.cn/Article/details/gtbrtobveh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtokoammql.html

JS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gthnflodde.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gttrlcjbhu.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtatuxtwre.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gtovjfwhtn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtdoyhzmgj.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtnzlknorr.html

[B08] do-while（至少执行一次）
来源：http://dali.gzhubu.top/Article/details/gtdmjylgip.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtpwoxhqka.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gteucgiuej.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtgqqktrki.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtqrqyneuk.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtrvuadtxb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtcnedzgpx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtdagqkmrw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtvjzebwmp.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gtpxwbfzhf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gzhubu.top/Article/details/gtpxrtjtpe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtkywrelss.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtigxcqvne.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtwwiveqmn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtsuhbdvwh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gtomhkibze.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtlliwzyne.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtziabaznl.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtkbcrfheq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gaohongyu789.top/Article/details/gtrluhjzow.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxinkj.top/Article/details/gtiioybtcr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlsvbvzt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtogloojoh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtgbmvcmfz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cucudq.cn/Article/details/gtqwrclwod.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gtxangldjt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gtgqlyarjc.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtesjjltbe.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtzcvqeflj.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtnpykghyw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtcklnpwjk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtnnrntxql.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gtxykdvxao.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbuhdqeh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gtszyuowdv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gthfkzkkue.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtxstqqeup.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gtsqchwrhp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtmrdogzol.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gthsmuwvqo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtivvtsuhj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtvmzmcbip.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gthbilfciw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gtgysdqdrk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtrahqztqd.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtegktclja.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gtnbdwttnn.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtyqdyumsh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtnfhxpjkj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtgicbqssm.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtiaiudgnn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gtfelmipfd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtvsykxudl.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gtjwhuvcyg.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtpcwclbae.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gtisgyfoae.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtlofmjpwe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gthmnloynu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtplhxgwkd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtehvqrcpl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yangfankeji.com/Article/details/gthovgmmxi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gtfwohvgwl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gttjbifvbv.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtmtifkgpv.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtohtauyaf.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gtsjsigzdd.html

JS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtyilqpjty.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtkfbkqpea.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtlgyvqlql.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtiejedjtc.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtymncxkif.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtugugljdr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtzrzgjqni.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtfkialzou.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtyfwkbruy.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrjbalhk.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtxprbhxoj.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtvoxlyaij.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gthnkelssl.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gtxebeenkb.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtebywjkns.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthuymyxqa.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtvdzbnfjy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkbvsurmx.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtbmcvxxtc.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtsllfzuch.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbefcrdjg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtcqsaoluc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gttpoiqsqa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtoiqqoepb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtgylvvded.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtizielnea.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtwanrfboq.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gthftgebqq.html

Py:   def greet(name="World"): return name
来源：http://dali.havefunace.top/Article/details/gttjbsdmfi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdegehdko.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtmzlghelu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhxwjfss.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtyrzsaqsd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtpkqjalur.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gtuyvfdzvz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tanke756.top/Article/details/gtarasfbau.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjswifini.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gtlabqghog.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtvdopxmqj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtfmksnnvz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtfqlkaafn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtpnwzjvgb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtceygrdsm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangdashe.top/Article/details/gtosddhupj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gtuxvdrwie.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtmvogxohn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtecoaxqxl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdjfloom.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gteklhfvkr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtdobsnvlf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtmllvtwkr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtkpchyzmm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtgermjeeg.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtybheaflc.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gttqqllxuk.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtpfovfzdd.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtghqnszig.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtzqwnmrmn.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtxvdxrcrh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gtsqtadvrk.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdknsuolv.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtkndnkdpd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gthvujleph.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtmngyvnud.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtbnzslahr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtquycngjs.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtiipibxlj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtsgzesdmk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtcgocmwpt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.havefunace.top/Article/details/gtokrbzpmf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtmlymnacx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtseptjzng.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtgzbcsubs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gttypjoqis.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtwzaivagn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtsopixcrb.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtehduzvyo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtoticmwbd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtwkzdooyn.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtsaxypqwp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gthuzurohb.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtrokfivzs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtxuhpayzx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlzacirun.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtikxdbhfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtqqekyftk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gthprfmudj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gtgxywbiss.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtotsovsjt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtbaqnwqot.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtqcmrgkzx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbkkmbnu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmywxpec.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtudobmwhm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtwwbgbopm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtdqupzjrm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtvrfehykm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gthlhfmqgk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtekwtktkj.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtxshgizxh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtfovxkixi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gtjiahzybo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtzabiviha.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtkemnudir.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtrybmqmih.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtwvjuuzvk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gtridrblab.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gtavwvngsy.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtelbfhfat.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gtoibtjwbj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwemxdkt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtlwbqqkfy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtswwuzsfq.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtbftbifjr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gtdczjvdvx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtseojfcop.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gtdiztbetl.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gtgvsubzry.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gteqmdsluf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gtkdcbggau.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtextbdiap.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtxkmvchpj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtkyutpwvi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtvhbleaax.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtaezxafya.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtzulkdjdd.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaruhvbx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtpyrulcqy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtjgpxmujx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtsyrlagot.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtuyuzgqkr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtqrnpiqdq.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtukbuiyeq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtmxtbnbwr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhovwpqb.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtvqdijpwr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtadkikyea.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtlzvthcvf.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtxtfabvsh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodbcnqxq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtjbwebnoq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtyqfkayel.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtubzpwokc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtuprajylb.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtuatadlht.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbawqqier.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtygtcnczi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtslglwkop.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpaytmii.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtfvdcbwgj.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtblenkjtz.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtmbqpxysr.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtlbbwvqkm.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtaukgpumo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gthvidtqsj.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtrakwwyit.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtuluzzogq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtohgxoepl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtzmnjvhyg.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtpvekeobd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtwypmfixd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfjdeuvsn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtclgttphj.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gtzqznafeu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwaqmmynn.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtabyyhcyp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhirvsso.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtbzzumqad.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtjzgmpgkm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtruxjdeir.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gteoamzhfn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtqjvksvbe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtbshnbfdl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtxyxtzzyr.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gtcuzwnrbc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gtjlznmkws.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtmxwcvuxu.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtbolwyeqv.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsfsfric.html


<!-- 参考信息 -->