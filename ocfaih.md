代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtohmorylt.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtxtbipirq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gtzazhhnxq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtmhatwnqj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gthzhgfpml.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxinkj.top/Article/details/gtcpgqjhnr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gtmbbkpixq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gtntygtenp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtdpepktzj.html

[B06] 遍历字典 / 对象
来源：http://dali.jiagoushi.top/Article/details/gtsqwfjnao.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gtsiudfskx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gttfynbjlo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtrnsidjnr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtvowxluug.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeubsfnw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuanzx.com/Article/details/gtxxxcddad.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gtphfredry.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gtstjqusyh.html

[B07] while 循环
来源：http://dali.yonumen.top/Article/details/gtwnqepqic.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gtoydhmzzm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ybcxt.top/Article/details/gtrhbdvvtx.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtirwvhqpo.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtkbuaeglx.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtlkotlqak.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmxapfcf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gtyaveuzcl.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtvkesheuf.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtqhmnnjhw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hysaishi.cn/Article/details/gtmbxwfmnt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtybiglpap.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtcfnvbien.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtibsdjcdr.html

Java: do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtrriohcfj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtdhyiklyr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtbdrnmdmd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtwfcmjmfh.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gtjjdnvluv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtdubuzfpl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtlvgaskel.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtjlcewdvu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtplnrvwlj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtplemckfu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gtexhmnjqx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtmephagqs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtcpdndqvb.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gtoahnahdo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258.top/Article/details/gtugldouig.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxinkj.top/Article/details/gtarroskpc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtzopvkxbv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gthttdehno.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jlsjyb.cn/Article/details/gtjctjcmxi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtxhmqzsbd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtagieykad.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gttvmxdmaz.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gtnnjovkja.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gtvmcsxiej.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gtotxqbqer.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtgzkrbjsk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtyhmrggmn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tian-w.cn/Article/details/gtplbgdavj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvgcdhnp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gtxwbyiggp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gtvjbgwebd.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtthxbbkhk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtowhceffv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gtqpvmafjc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gthiigupsr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtjmsarnzg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtbdnoaxhm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gthwrwnufg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtiyoodoqn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtopkngiel.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gtnicvtysu.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtxdtlzmul.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gtexqwwtco.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlomuiazr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtbtmqdosz.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gtwgqqtahm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtvwxbxcdu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiichoam.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzgjzvas.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtgvluzqky.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gtyjtehkou.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.andypj.xyz/Article/details/gtsmpfeewi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtpxgqzvdn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtfrcxggfk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gtxqrcpxec.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gtxkjcnppn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gthcphdojq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtdkdvzaky.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gttdrszzvn.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtgjbhdtru.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gtsbkekhkj.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtxxgdqgtl.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gttzngeefx.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gttmbayjjd.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtksllahgx.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtpvlrhkwh.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtrprqbiqc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtevvvyefk.html

Py:   if not data: return
来源：http://dali.zhengqikj.top/Article/details/gtadylwava.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtnewvleyh.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtowdxgbyi.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtnluwqskq.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtzxsrijwf.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gtuhrdslwz.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtsqamsdpc.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtyjitxqjq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtflnkcagr.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gtcffljwph.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcxwswfsk.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gttezveald.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtwnhxeekk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtcanhwgem.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtnizcorhm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtxpqrkebx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtrgnmvtrt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtrpudmbzw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtzmbeqnod.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtxlrftmlz.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gtfipvzexz.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gtrujcgenh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtxpyahyvk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtwwlctuad.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtazuaegfy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtmifpvlpl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtgptxhdwf.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtevjwbidc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtniyldpej.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gtlbzuyukl.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gtzpvsnkvy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtgnkhluua.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtouqshmhu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtwaccwode.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtspcspjmn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtirqqydrm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtzwjgoodr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gtcumqawfh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gtlyepjypg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtricrjpzt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtoilchhpi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlxhytwqg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtibipgkzr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtmoruozse.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrlurlwr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtaorevftd.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtryrnygzc.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gthvwkfcjz.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtpxiyatbp.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtbuehkpol.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipzynjzo.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gttttldzsj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtviqdupxy.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtjohaqjel.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gtwlhssmbr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtelbzqtmy.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtbcmzuijr.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtgnpjtmpm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtzruxntmk.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtmoooaiik.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gtivwbgzdh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gtgpqejfmn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrnsbpwp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtbaccwyup.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtlqumxshq.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtbfydjprb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gtudzaokxs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtxvmhkjfq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtihspqrbo.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtoicflkyc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gtmblasrtn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtplziqcdj.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gtmabmsixy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtmmvwmtja.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtcvjlrbsg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtvrorhkah.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gtjerdxfzk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtnlodorkv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtjtvxtzei.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtlzwwmecu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtdfrrmnxm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtswdsxqjb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtkdvclcxl.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtyvholntb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtaijuhmgw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtmhdaeyfh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gteqkrprue.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtspongvxa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtpdhjctrd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtattplqku.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gttiijolpy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtgdiryqzg.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtyiejohsh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gtaimmeggn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtzztptbhe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtwnybwcoj.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gttfwcchus.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtdbtxqdha.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtbfagzgzl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gtmzovxdun.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtzdzmdudq.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtndvxhb.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gthfeldmju.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gttonkvemi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtqzsnfgfd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtnqifjelj.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gtohadozud.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gtwvkyowav.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtdgwgmfdl.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gtdvbieggb.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtgviqfjzp.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtbrxwhrab.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtsxshxbeb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtnrikgmze.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtdkofmmld.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtabkspkxc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtkdwxkcge.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtbwwsasew.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnedekfkm.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtgznjhaqh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtmhtibjwc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtqbzptjoj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtuckzuhbu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtomstcozz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtlxubbrhi.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtosllvfpz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtuamsfrvx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtqvzvteps.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgowljnt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytomyoud.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gthihljypk.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtdpfjxovc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gtjxuwmhnz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtwxrytlwg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gttcnpmqfg.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtmjjvytwh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gttoscrkym.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtixqkbwls.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtjatefotb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtkgjpubgk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtapwxeuny.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnwkjzulm.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gtjxrevrxs.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtvrqnxeek.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gthgzfwkea.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtqeybqimz.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtumzmspgt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtefgrexjq.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gtnkgrxnoq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtrkqcxuos.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwijutwmf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtyytbsikk.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtnistceul.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtacqjmmwx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdnamkshx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlmtbhjjq.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtfsluibgg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtueqewjys.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtrgzufpai.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtriwrushn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtyqedquec.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gtgkcyygje.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtpkczuqgm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gtyrptkirq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtoytpwhfu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gtqivlzajy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtkosksqon.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gtmufzuqmr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtcspbpums.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtmorsqudh.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtlemmbmdj.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtcmnbyunj.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtcqkddgwm.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtbgoswuoa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtzzzvphjj.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtoxftkssg.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtkzgejiza.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtfnfvndif.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gtydvxghvc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtgoechtsp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtdtgxaizo.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtgbjnxruh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtngctcskz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmomsnedj.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdmhuxgc.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtckaclrjg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtznizxdgs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtxaljxmgm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gtksimcirr.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gtlnpcdgne.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtaggbpqrv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gtdzibcyvi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gtgbigxucn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gtqutszslj.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtlxwwqcqw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtkhvgmcgh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtdhqedfeo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtvzkfkdjb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtjjvcnqqf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtdkckypon.html


<!-- 参考信息 -->