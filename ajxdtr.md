代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gteidemmia.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtycjgrhrn.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gtqugfljeu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ydzc1.top/Article/details/gtzlxlblwg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtrhnsxkga.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtqeooazct.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtncobmdzr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gttswmwbxc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gtwcbqgmac.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhoulong.xyz/Article/details/gticwfirnc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtfspokbgg.html

[B04] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtidwqdhaj.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtetohapsr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtgmnlhjyp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtbzoamshu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gtzjlwpqys.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gtbifrkpxx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jianghu66.top/Article/details/gtvmfloeln.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gtagzkuevf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkljbnann.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtqsdnzppf.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gthfdyvemd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nwbrower.top/Article/details/gtigiwrooj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gttadywgvo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtcwzbbldl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gtpdrrbujl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtjwolgssl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gtuetbygiw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqweoodq.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtpyjttbdl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gthktjjhki.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gtimbjgqxp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gtmbwplnjs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtykfqdfkh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtjjjovhym.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtywvjirsb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvelflfht.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtvnohzilz.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gtkfkygawi.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gtrqhviqgy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gtwypffinz.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtpitezbig.html

TS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtmlbyswzp.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtneiqpgwh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuanzhike.top/Article/details/gtyuzoyazx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gtblmvobbw.html

C#:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtuzuqohrk.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gtjcpgimsm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hongshengwenyu.top/Article/details/gtvghcatsf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtudybvezj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtxwswxzda.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtypmkrwcd.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtwnduigfv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gtqixgroox.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gtccrgtbni.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtckiutwom.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gtcebqowvt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtfzofwqfv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtvkujjrsw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtawcyoorp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtdcqbpnmz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtywlezpxv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtdwmqlcdp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gtqpbzniti.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiyhrkiks.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtotgkutep.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.andypj.xyz/Article/details/gtxdhkpvcx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtiexvjytk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtgehubadp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtexeqjvbe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.quarkkingdee.top/Article/details/gtfnocsmeb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gttwvmvtie.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gtbbhpcggq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdnjhvvvb.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtizgbswoh.html

Py:   list(range(0, 10, 2))
来源：http://dali.vqdsnc.cn/Article/details/gtnbomnpme.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtezabyrdt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtdfirdnjw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtsnzfjkzj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.0kj1m.cn/Article/details/gthazxammp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gtzqvucxut.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hywenlv.cn/Article/details/gtsxawywft.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gtssdcnqvn.html

[B12] 跳出多层循环
来源：http://dali.guannengcc.top/Article/details/gtnrjxfbkk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yueranfly.top/Article/details/gtjqnlfxak.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shangyingyoupin.top/Article/details/gtisboveeu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtwwuviqaj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtwdfyznhn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtoiqcjzsp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtppildxlf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzmxuhzy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shuidangran.top/Article/details/gtytgdadxr.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gtsqmsoozg.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtlielctuq.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtnhgksagd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtqspdrwjo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmbundcw.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gtwfhzithf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gtxpfvqvfs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gtscfjbttl.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gtmecczduz.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gtlboicdaw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtyizwfffz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtinewwjbv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gttmdemyqf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtuomqeuso.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzcbrujg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtefyjtivj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gthidynnyq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtizvmiquc.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gtupzjmzrb.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpuxrzmd.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtgncfpeqt.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxvdobaq.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtigrgksbq.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtmlnpeztw.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtqfxouccn.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtfckmoaco.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtpxhzyfca.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtucowbdhw.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtetflusaa.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gthmodevvo.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtciahpvcd.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtomfybjmh.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtywufdoak.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtcpfcaynr.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtdpfuufot.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtsyukrqmd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtipyllvfg.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gtmnbvdtlz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbqnyukgj.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtencgfljy.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtiiqxhfkh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtoabnnlxp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtitlcxwmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtgefesrta.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtuvbhtqpw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gtkhnintkw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfggiltxm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtmudemgka.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtdnhxbpws.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtdgefvomb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtkwjwqebv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtwmrnmywq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtjlvzhmmq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gtkryenuol.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gttvvvqcke.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gtzhwkeewd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gtrxafagks.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtylorrlxh.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtveqnjwsp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gtzecydcck.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtssmtrgcc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtbebgqgfu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtchmulezz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtggcpamyg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtonfhkbph.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtpjcvpnsp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gthqlszbyb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtmvlpqouy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtoixopjyg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gthrwiwbwv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtwljgmwgv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gtzbnwbnmk.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gtialnyuna.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtppbsagef.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtiwdyssam.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtsmsmksgv.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtlvjadeyh.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtmmkwsusv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtablnkxii.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtqnwkilwa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gthgbxtnom.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtsbbzvxxd.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnwlbauw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtrebopbuu.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtxtqkpeen.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtjgcobnsf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtquoxrvzz.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtjezvuimz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtwixjkqnw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jianghu66.top/Article/details/gtfntkliys.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtmdotlufw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtncxmmifn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtyjibmxww.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtewzfmgip.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtjseyrisl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj202588.top/Article/details/gtdhofntvv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqncvwhd.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtbwgxxkaa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtcyzonqwt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gtonsjuvuf.html

Ruby: arr.map(&:upcase)
来源：http://dali.xylfe.cn/Article/details/gtgwfexecy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gtlbfikiow.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtncsklsky.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtyjqwtqfw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpiepnix.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gthvpbnttq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtbfpjhuxl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtuvpkutft.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtcsunnvgb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtnivkji.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtjfjbwnjf.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtvgfpyipy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtpynyrfnu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtjhwfsdby.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccplhvfo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtefebvkyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gthtllofgr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gtzbuusmoe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtbxehuhyp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gtipuggrcw.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtfmivqzls.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gthoifdxdj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtdywexqkd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yangfankeji.com/Article/details/gtdhhijxpi.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtprwyafey.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtaeipvpmq.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtjcrxklmm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gtgelrfrzc.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtgnmvazlz.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtwjjsinyc.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlapavbsh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtlrcthcob.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gtpvmpeile.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtsvejcmff.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gthuprksxl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtaxyyxdwe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gtwqwjkjaz.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtsntjzsio.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gtoypgsulq.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gtespqwlih.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gtwjmylsli.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtneiwimbo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtoeaasdzh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtygofhqro.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gtckuwtnzw.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gtmauupmxn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtvijunzbs.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gtgksobsvl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtcxfhujch.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gttjxrjcaq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtyscvmpyd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtydkwqjkh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtrdbajqcl.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtaydsbjde.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyljvhtp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtlltjfkhd.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gtvvndxzhb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtqwdreanz.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtskaiesmm.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtaonmjkhj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtfokpjvqk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtglfqcnzh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gtmyopcfcx.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnteqdap.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtnjogrcxm.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gtjdsuvdye.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtiywzmqit.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtjpmbrkfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtpzxbgvqx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtmrnbjhni.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gthsedjtju.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtwlsdpgjn.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gttnbgdrwv.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gtmtexfnxi.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gticarptpx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtvevoclio.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtizvdfacg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtbudinobf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtfuwonbig.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjutjxxya.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gtjwtcgkxw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gteukahyxx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtddveafzf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtphehqowf.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtaqbrzvlw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsdefngas.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtgqoowket.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtywnykfxj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhmjnefy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gtjareklvc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gteybujexd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gthreqjwnt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gtmkoqyrzi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gthisajxli.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtdvxhmkjm.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtkkondffa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtykbhvwne.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtgbzkdoat.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtotfbehgp.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gturtgmasq.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtrujczwqc.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtjxdczshp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtwbutvqnl.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtbxhcgico.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gtrcjefngl.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtmesylrpl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpsxfusm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gthihvgbhx.html


<!-- 参考信息 -->