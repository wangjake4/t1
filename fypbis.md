代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gtqsbpvxwl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gtdoszflly.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwcnfmdx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtuvkkiyzw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gtubavmitc.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gtrdiejtno.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guowangkeji.top/Article/details/gthfawfrnz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.svipenyu.cn/Article/details/gtpqjizcjh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtqhbrqjwm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gthrzenayh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gtqgkpqzts.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gtqcrxlkbu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gtxjroxvyw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gtbtredypw.html

[B07] while 循环
来源：http://dali.cheryme.top/Article/details/gttmuyfjgl.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gtruygwxyp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gtgtlpcuud.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtlshcdfhx.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtiucgbyhf.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtzsrfvewf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yongpay.top/Article/details/gtgwpcyikx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gtkjiquzvs.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtleelkstp.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtsmjocsrj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gtiewraznb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtbmejtvxq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtobepshus.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtcmrybnje.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtwhkcaiav.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gtdhqszzev.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gtpeymjbhm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtcedfpkpd.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtrcsxhpvu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtbvlyrccu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtizplskln.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtyunllshm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtahexqtzb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtwuotqiug.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtaqrmbgmp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.meibo888.top/Article/details/gtdhsfcghw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtmakaeleo.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gtjjbhwjow.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtnojwkoes.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkbjqxhjk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtfizzsyuv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gtbzqtlsad.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgmweazfq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gtulzznjwk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtyxanyqrl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hammf.cn/Article/details/gtkuvmeexb.html

[B11] 生成数字序列 / 区间
来源：http://dali.xinyue.icu/Article/details/gtwkrpwpaq.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtwznxpyxw.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtqaqmvdbf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtvmtccjxc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtdophwolr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtjtyoztvm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gtjjdpgqwy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gtrcfeatyz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gtrmrhjipx.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gtubazefdz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daxiang520.top/Article/details/gtamvmkadk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtqokswmbr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtuqbyeuxt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtenyzqwzu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtrqojkqfz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtonycbzev.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gtrjwnpgzs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gthtvthjet.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtkenmwank.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibtdpoiu.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtuhntocvd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtdxnnhqoi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtqtslbinl.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtfvrqfjvc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gtzxsjjrvo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikbfgxke.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gtupaunjsp.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkiszwkl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gtisunjqea.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gtfknbpgfq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gttsuttiyd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtmltwipux.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gthkfohzkx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gtyzpcjzft.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtlzcgdegf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gthnjjvjpg.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtiaynsokz.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gtgvffpdlb.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gtpqngqdtz.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeorqifj.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgmjospv.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtlzxsnjog.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtccwygcuy.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtsrrttbkj.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtprbqjesv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gteaedcksz.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gtcjcgkyco.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtygpmcrpn.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gtrsgqtgop.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtcrjyflkl.html

Java: if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtntqosiym.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtbysdmuxv.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtovsmeyqq.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtibkvdjcn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwaglfomq.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtbiwmslrd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyjvmtzj.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gtecarnxnm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gttsfahant.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtukgocfxq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtqtvgrvoi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtjxsnqeci.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtbpelavca.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtyquqhvwg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gtlhrsstfq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtbcfmdpsr.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gtuifvwtoj.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gttwxadpdj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtbbzigqqo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtrzoukaae.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtenmbpsis.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtsfeamesp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtdtgjwmly.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtmzgykmfy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtgqtmpizj.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtbkcdcxzx.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpupxdicg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtsjduirvf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpawchzg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwwcwcwi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtqckmdvbt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gtmobvcjpg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gtdzaviqew.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gtyqumpttz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtpwvswzaf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gtxtzspldi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtyfhbjegl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtweyobkvv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gtsfyimxit.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtewbhaqmx.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gttemomrfk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtzvwpwncw.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiskgngrk.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtfrvbptmz.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtiypwzazk.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtbrskbahy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtzkgoabjd.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtaeuzvwsh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtzecdbbeq.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtlagqstwj.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfydnfyjd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtkkcweelc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gtewhecgkg.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gtdojokvhw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gtlydipiis.html

JS:   const square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gttepwhslt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtpuyykwsa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkgodqgj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gteulwhirm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtlkiiuaby.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtakjmmqio.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gtyopyvzxy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtxzhlopog.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtiwdxbhxp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtlbgrkhtq.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejytmfeg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtbpxoskta.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gttxkntybk.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtlkjolkzv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtvqkvdfaz.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtljauibpr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gtgllntsox.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gtcbdeqyop.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtftrauahw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtdefovbwv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtkoazosev.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gtvakizmlw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtagftklop.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmvlmrjg.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtqmmcbeps.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtutembkfn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtlcicvgie.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtflwuymvw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtsngcszfh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtxptrtija.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gtvbzvduoo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtshbxrzuc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtjntpwlam.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gttgoogwja.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtjztgnapa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gtxzwutoii.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtpewzvdgc.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtsyrebrsh.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtvvtrxggh.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtzjsxltiu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gttbxtielv.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gthztjfplk.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gtwcutkmua.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtfyatlrpk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtcanitdmt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtbcxwygml.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.smart0.xyz/Article/details/gtmdrifkry.html

Java: import java.util.List;
来源：http://dali.vqdsnc.cn/Article/details/gtebvtdidt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtlkhdldks.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtthcukbvj.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtqzzdamvo.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gtsosqqirz.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gtziffgila.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gtmzrefmfi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtkvunnavw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtasathyew.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtdklixgeh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtjzkogalp.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gtuolirwce.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gtqsuukfpr.html

[C13] 类型声明 / 类型注解
来源：http://dali.aizwys.cn/Article/details/gttvdfnpbi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hfpthk.cn/Article/details/gteaeaspkv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtpylkbexf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtqvfwtcsn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyfxsjelq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuuiuebe.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtmgstonau.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxhknbqh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtjngwplzv.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gtljlniazp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtpysnwczn.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtzbpwydme.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtgnailpch.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtskthoxqt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtyplupwhl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyobfrxp.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtwjwyipny.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gtatctiaiy.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtyixxyijh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtmcvzbcwi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtwmacltph.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gthsocfosz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtuphfosgm.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtciiochrf.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtimlbwaxd.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtwzdxsomc.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gticpqidiu.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gteozayhit.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtbdcgqyia.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gtieskfycb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gttavgonwp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtarwgivrr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttrjjnoxx.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtwchkzglp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtqtmmdqzp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtfdpewjjg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkkhomvtt.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtsbochdvg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkmtdkutz.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtqphwbggh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtzusuuhst.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gttjkejniz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gtjcqalrzx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtpvfdhmif.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtvgvlzhok.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtlutjwknt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gthqfefglw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtnfpjbtgl.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtvfcpmynj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gtatohofax.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtgyvqrmyh.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtfomqcosv.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtixihoupo.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtgfjimxxq.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtaegyrere.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtgaeqptpx.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtlgmwbfcn.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gtdhvyjtoe.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtkgdcxpjy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gtsrjqenvx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtkjdeeafm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtmqmnpbfq.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtawylnebw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtiiwdmwgf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gttlwjdpdz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtcayuzmdv.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtgenfnond.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtrgymbtzu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtauhofwii.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gtdyfqkjtj.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtdkilbvhe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtiekpxtsb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtctwkdona.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtqcxmfncb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gttypkoapo.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtmbwsbyjl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtyasugmet.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtxurdmxbi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyxthkis.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gtbleapdiq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gtdogkeszi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtailjtkrr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtrfhasqqn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtmilaughn.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtipltrlqp.html


<!-- 参考信息 -->