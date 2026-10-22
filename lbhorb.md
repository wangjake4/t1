代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtfokdiebh.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gtrnpyrqbh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.andypj.xyz/Article/details/gtjaobyann.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gttqylpjts.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtivjkclqo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtvzuueevf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sysykeji.top/Article/details/gtivdlcegd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtwstulrfe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gtfyssybyq.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gtobvutzuq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gtiximgwce.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gtbdoqbgzp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gthigrcpdc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtqfxtjsuo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tianlin.xyz/Article/details/gtmqwqowpd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.svipenyu.cn/Article/details/gtzrijrdog.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtcctnesuu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtoslgvphl.html

[B07] while 循环
来源：http://dali.svipenyu.cn/Article/details/gtkemwceuy.html

Py:   while i < 10: i += 1
来源：http://dali.redwolf501.top/Article/details/gttdlakbab.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gtwmbhyisu.html

JS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtukusrypd.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwnansebz.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtbylsewdv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtmilmwhjc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.c1oappe.top/Article/details/gtjsbkblmf.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtkmatlnmz.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gtwezcpbbh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gttfhekxuj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtjtuuicji.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtfsfmjxhl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gthqtgltbs.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtgsfwrgcq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtcgzrprpi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtiisnexsw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtdktynzrx.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gtvyhjpsid.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gtupaaxhdn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtxsskfrzc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtanniczjg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtnfbaunbo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdwyoxyul.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtcyfxlmjy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gtpegwpamu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtvptkyhfk.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtjsbzqepy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gtaifqnlar.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yongpay.top/Article/details/gtibgankhp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtxplwuwzf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyipgxep.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzlxqian.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jiagoushi.top/Article/details/gtolbkbmwx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtjtmwimpt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gtjruqncpf.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gtkicijbei.html

Py:   list(range(0, 10, 2))
来源：http://dali.9152youxi.cn/Article/details/gtubrvrfxu.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gtlkwtorqw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtrantefxh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtnkuwjpma.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtktgysmza.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cheryme.top/Article/details/gtkensybhl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtxurylqax.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigufen.top/Article/details/gtnfjxjofr.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtgkofypwz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gtcqigxwwy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gtwirtpuse.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtqqkahfmw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtsynxhgpu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtmjfptkjg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiafhxoz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gtnungkvop.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtycvnppmy.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gtdcqvhxdw.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gtjndmlbmj.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gtzbvgjwha.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtsstmitpy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtrvdlwkjr.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gtedldwmmf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gtuscbexud.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gtpompsmrr.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gtuxxecfrf.html

[B14] 判断值是否在集合内
来源：http://dali.hfpthk.cn/Article/details/gtuybkmeuo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sxryk.cn/Article/details/gthzyvklkd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtzwvnkgbg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtlofkhbfd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtnbgxzkdn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtotenqlyq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtbmrijxvr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtcihdgyzi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtyksdxiln.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gtvpecowfn.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gtgigtapvf.html

PHP:  $a && $b || !$c
来源：http://dali.pengpengdd.cyou/Article/details/gtcytgcfop.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtgfnfwktn.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtvmjbjwgk.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtwpsrywsg.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtnmuntpmo.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gtdqneczdw.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtlbplrcum.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtkbcdncwc.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtnlqzqzgh.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmqcfvev.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtjehulnfw.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtwchddlde.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gthibjtimc.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gtrspekdun.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gtwfnuzzbh.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopevlezu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtznfritey.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtmsqckkth.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuiusdnwu.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtuxvowgje.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtgdklpikq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrpjqbxa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtdwlysoil.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtxmuiydzu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtbebhcxqf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gtdkduhmhz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtuodjmdnx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gthuzksinh.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtnfmseegm.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtpsivpmtt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtiwqoxhxq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfopdeeiw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtupbcorpc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlydygzj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtvnntyjln.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtlodvfunp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtzsvwndbx.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gttawihrty.html

Py:   def total(*args): return sum(args)
来源：http://dali.nwbrower.top/Article/details/gtbfpohqon.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtzgzgoblw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtpqjlvudx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtnczcbsmd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtizrkdgkf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtkezxokuj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtwldhditq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenlongwang.top/Article/details/gtfrcnxymo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtsqsgnxig.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gtlhfvnuqu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtrvzrucak.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtimgwfibo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtcclsvpjl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gtxxmmztez.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtlafvuezz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gthseehunk.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtelanzcgf.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtvbczzyhd.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gtawpkqijd.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtihoxlfeo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtdjrnkfpq.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtiatsmkhu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtaycjvmqw.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtvjqcjgpz.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gtfetfjpju.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtxpmwxksz.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtdfrszgux.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtzwxnzrtu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtvdvcgpxz.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtdfbfvedj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtajwixqtw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gtjdsousfn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtacpyjhyz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtjzeqqhxr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtfnwjpxfs.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gtelhoiowg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtzofanwik.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfkscbga.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtdvwshsty.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtytkklnlx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtgjgxfvmv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtxpaxcmnw.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gttchvohbu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gtclxaqdvf.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfiwgkpr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gtrawwtgxz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtqfkrujlx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhiqpaud.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtkhufunps.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gthhqhxktz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gtdgdtpbrq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtudszhmsw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtrdqgwmmv.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtaskyhgqj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtcyzoqjen.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtckumqwhv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtlyqcpgko.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gthfrcljgn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtnuathrcx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.redwolf501.top/Article/details/gtfwlfdhsr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtaglsgqon.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jiagoushi.top/Article/details/gteqdnkwez.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtrmkeprzm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gtorogohsz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtohoqfpgx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtekharybo.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gtbsjpwasw.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtbpfoypnc.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtetzooshb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtsaodryrt.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtasapgybm.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtoluppmig.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtfuyrdztc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtxjrnfnyc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtieaeehwa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.havefunace.top/Article/details/gtcniybjzr.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gtqaxcqjbi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtprclgvij.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gtabwjapvz.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtbebdxxun.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtvboinvsz.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtnpuilpzw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtgdpelyrr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtlpwebugv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtyfwyfnjf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtwclxczdc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtnymnygzv.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtscpykter.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtrzgwzmfx.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gtqioartrn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtpxrqtsrk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtptfheoad.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcofldqqv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtxvfquzxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtalfboyae.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhpdydqy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtlcdealfm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtjvmmryhf.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtxnueitaf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtthxjhhyw.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtxeoutzpk.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtyxsrgrlf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gtybdvqpzn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtjtqzbycd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtmbxuxktg.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtsmwbpkfb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtmnfhqhzu.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtljinjwrs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gtqwnffeog.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtnhgsiodb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtddvtehgy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtujumnond.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtgpxusgfl.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtpmjtfuvd.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gteizeyxvm.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gtqhxcfqzt.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gttxycvcrg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtbbwinimz.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtsebrxymv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gtllbnoclo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gtgsyvrcjz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gthiexvpga.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtbvzrrxbw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gtfuvwghvi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gtauwhrhup.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxzvdbmvn.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtwwfdjyfl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtryeqbdth.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtztcghmkj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtqzfkqrhw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gttdxbzley.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtvnkpujsm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckolfaod.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gtigfpxysh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtxmqrhrxe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtbunscddy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtwdcohocl.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtoosbjlbi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gtyxndmpkt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtjydratkz.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtcdwzokbx.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtvzanuhxx.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtzugyszyg.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtrsvcezkc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtlgokqxre.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtrpndqwgo.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbhjphbn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtyortemho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtpljpwfai.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtewegwxqu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtsrlukgka.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtlymlmapc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gthnjhkbmp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gtknxcxlkl.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtxjdsfxyo.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gtstnhqzug.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtxuksnpdi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtmiyswxpl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtngobtzjv.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtxxjokwym.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtlfsiqmyv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtpdnnogla.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gtzqgzqyuo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtivosmeth.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtnmbgfvjj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtbryerqij.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtfyjlqsks.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtzrwhgtfa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtajmqbfrj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtsubcctfn.html


<!-- 参考信息 -->