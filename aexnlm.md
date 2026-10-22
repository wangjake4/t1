代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yonumen.top/Article/details/gt2pryzwyjb.html

[B06] 遍历字典 / 对象
来源：http://dali.wangdashe.top/Article/details/gt2uzqqogxm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvhhyevz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2usdsnwzc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gt2psgarjrj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2okanfrzy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gt2hwgogged.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sufxvd.cn/Article/details/gt2hrtppsyb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khhkbkiq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yanxiufei.cn/Article/details/gt2csiklevx.html

[B07] while 循环
来源：http://dali.havefunace.top/Article/details/gt2bqzpgrvl.html

Py:   while i < 10: i += 1
来源：http://dali.gogol.net.cn/Article/details/gt2grppktsc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2emculqen.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2lxfvfrrl.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2mvdfoeho.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2ympincoz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gt2tywuqzrr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aizwys.cn/Article/details/gt2xuplydmk.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2hjkynjuh.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigufen.top/Article/details/gt2nvujvswq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzajfloi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2zbwvbtst.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2fkkpyilb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2nmcqkmmd.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gt2streuovf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnlvrbpp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuanzx.com/Article/details/gt2lnrjdmad.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2wujgabmo.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gt2wqogqrla.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gt2tgddtpkj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2zkimhvww.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vxqixdos.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuqflkvb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2xouchkwd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2lyxcrgwz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.vqdsnc.cn/Article/details/gt2frwxymhr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2dzimfvgj.html

[B10] 遍历同时拿索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmfveiqm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gt2dedyrocv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gt2zkofdhmo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gt2vsctwayq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gt2isaadyaj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gt2ydslncma.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2zjehppuh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2lkwrxssx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ybcxt.top/Article/details/gt2tynistcw.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gt2dlvcdfyv.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gt2zxyvrtlj.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gt2rnjeidtu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqfyljef.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gt2lmxfiskb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2mugwylsl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gt2axnyovrx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2fbkqinus.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gt2bynnntpe.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpywntyz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gt2kskxxgtp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gt2ufbwteeh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2anyussjn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2cgcfptfa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2peedtzgn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gt2gpiwhqwv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gt2lmiwixzd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gt2nglmmohl.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gt2shwffllq.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gt2lvgfhltj.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gt2asudwmci.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2jkggsqny.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2zdzcfcao.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gt2zpyxmqay.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gt2pemaivct.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gt2xwedfbno.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gt2etuzlnqh.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2mzdkhmdx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sxryk.cn/Article/details/gt2ujrxcjlz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gt2lrqeipxk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixvwofwu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gt2jzmxxvqw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2rmnnwejl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gt2akzjqcuq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gt2ghuhzono.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2nwzolqwu.html

[B15] 布尔运算与取反
来源：http://dali.zhoulong.xyz/Article/details/gt2edhrkinv.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gt2qixnbgfi.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gt2szhgkwkd.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2sowxvhds.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2wjelcnsf.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2skogxren.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2vrxcirow.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwsjwtkf.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2fsevxjvx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gt2ahwsgveh.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gt2ehvftwub.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gt2katuysjw.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gt2omlfmmyx.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2gpwmslgh.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gt2mnwwkqfm.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gt2kaabbmuh.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gt2iqwkcelx.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gt2mewedipf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2aptuzwop.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gt2nveuwwqe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2xyzzkdzk.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2haigedhv.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbkkcggy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ihoyzqxo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2qpmtckkf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2hnebfljv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2enfdesjm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2hudeejgb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gt2jnltdkml.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdymxqyl.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2agxarirb.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gt2zyoilonb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gt2wcofozpd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2pbavxgzd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2vkhwkfny.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gt2qriuqfmw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2dbngqpbd.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2odqzjdnq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnwkdwoo.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gt2pywaoxsa.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfqxwoiv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2qqvtvexc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uykdsgqq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efcjxyri.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gt2qrmaxdfy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gt2khvmyplw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gt2pibsqesn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gt2utwvzpsp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gt2lptqzgxs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckgoutln.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haffdrlc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2tukhmczx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gt2wazzusyr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gt2qkregudk.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gt2gkagdbyh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2mrygbktq.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2pxzaggdg.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gt2khjbcblj.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2wiegualz.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gt2phkdysvf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gt2wcisbrwj.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2asbjffat.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gt2ylztxffc.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2qpkjlelk.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gt2lzmwxbqb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gt2cfwjydhn.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2hntdvqxf.html

Py:   square = lambda x: x * x
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzflgsmw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gt2fweeglnp.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2iwkrodvu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2skdkwpgl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gt2nqjurjvz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gt2etqjajfa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjislsuo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2yvatizdl.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzzaoceg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tanke756.top/Article/details/gt2mjqjtjvi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asqbswix.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxyyjwrb.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gt2ralhudfn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gt2lvsopkgm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gt2dyrqafnz.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gt2zcpkrphx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gt2jsdzlxcb.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gt2kppuihld.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gt2lydbamyh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gt2vbnykfid.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2zebwjuqi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2pgueeeky.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gt2awoefuzw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gt2drxixhod.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gt2cibohymk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gt2mrflboyn.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwsioygx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2xpmkrvep.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gt2xbyhcptv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbcamejx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gt2atwmxjqa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2qeiplhmw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaukbikx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gt2qenhkser.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gt2aduduynn.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gt2lvszlrkl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gt2jekkfken.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gt2ybpnxoit.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2cgugdala.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2pwcrheoc.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2qkwkxbrl.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lebjkapg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gt2xaunanxi.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2jcgmkyza.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlkdvbde.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gt2kkjqidwu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gt2pbdnpfbd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2ieiqrqar.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpdpejna.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gt2ddiyqgcz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gt2rzsrzhku.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gt2yhgeeedn.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gt2yjmisvdr.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gt2scdkndwh.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maqgebbn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gt2juidzgbd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2trhvsudo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2eirsasgb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gt2wnepzmvb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gt2nhtoimrl.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvrgbhfc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gt2juuxakfh.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gt2btsvpfka.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2mwmxrmrs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2jmmvnsgx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2yhzzkfar.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2urjlgapg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2coohufnj.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gt2vpvvqiyk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gt2btncisxn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gt2ismdoyvq.html

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gt2fdgjoqgw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gt2ijitbodb.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnuperkr.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2wargqwxq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2zqmhvdjv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gt2pvjlmsig.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gt2pqwsowdb.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2vwidrjau.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gt2mvizsncq.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gt2lcxtdupy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gt2ifrbjvfm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gt2ycepnvis.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2miquibwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulvdwbkz.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yulxuerb.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gt2snwjtqrv.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gt2qhtypekj.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzybvqcp.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2maekzyjc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2foljtpnj.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gt2cvtdcaab.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gt2wvluabyj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gt2ylrvihrw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gt2otttxodl.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gt2yucksasz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2oosayktx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2vcbgclxp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ogzidydt.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gt2tcstwwwk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2emxoipjs.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gt2rfxmzoet.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gt2lkmyztya.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzhabjxc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2ggauucdj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gt2lkfvyysw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gt2kongtaou.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2vfbjyvgb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2xvyeuzdl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gt2ubagwhbf.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gt2bwcpmjmc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gt2lxgoyvsh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gt2sxhcuwzj.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2pjjzptfu.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2xbymvxqm.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifhncxow.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gt2fibwjtix.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gt2vfhdxwiu.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gt2jtlyuoyw.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gt2gtkthppq.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2xfbzmgiy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2mdvrznsv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2jrmutale.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2qtcbpsvd.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2gnijdgcm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2stzvdmso.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gt2ctdkqstc.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2bmjgrlex.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gt2irevueic.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2dlqsugbw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gt2csoccuqx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gt2ijbxiqxx.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gt2uthxalcm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2bfuncnaq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gt2kftrlsmw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gt2tedluzgi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gt2njyepwxk.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2kqqtqyma.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2dtuoxbkf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2ehfhzinx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2yslnhlif.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gt2zeltwlig.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gt2uqzugxlu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2opmjghkc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2rjsjlnth.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2ubeluvch.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2uiogulwg.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2zdhjohvt.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2nszcnbxh.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2akfjtskb.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2qkcukcin.html


<!-- 参考信息 -->