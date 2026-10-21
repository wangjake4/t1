代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtqlzpkeae.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdyvaggtg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gtnqjazqhg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gtonochoch.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gthijlecph.html

[B06] 遍历字典 / 对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaioeyabq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.kuanghao11.cn/Article/details/gtmrerybfh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gtllkxawnf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtgxgkipxb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtlkkhleqz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gtasjpscqb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xylfe.cn/Article/details/gtiqwhdztz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gtcgianhxg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtavfirsaz.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gtsehgsplh.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gtznzigzuk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtcvwccjtk.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtufnbyqjl.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtflpiclvt.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtulvhejzo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnxiangtu.top/Article/details/gtwckyzsow.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ybcxt.top/Article/details/gtncexnwgx.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtgxdooeyi.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gtcdfkcefq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gtzbmqobhi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtpttbbhfn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gttmcubddf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gteuhipebe.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtzqjbtkmm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gtmixidlcc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ehwqpu.com/Article/details/gtmgqrlafn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtavfdgvsb.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtebmqssly.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gttomwteue.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtdrrgfgin.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkamucmz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gttdyhjzks.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtamfhholn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtsmbnvinf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gtwmwgutal.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtzwbzkbcc.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gtrcsuyhcg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zdqjudy.top/Article/details/gtkpbhrgsz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gtiljhpjbt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtausoxkvb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gthxnewmxd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtgqvoyjjx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gtkamsflmg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pycfn.com/Article/details/gtvnrtmakj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtgneavlyu.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtgslsckjx.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gtspnugdeu.html

PHP:  range(0, 10, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtwcxxzybx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtpybfoefa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtzmvalpnf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gtmsuvmmev.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gtjsdhqhrl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtkaqdlzrl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gtinskujwq.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtczfnwdjt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gtlqbozdid.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.smart0.xyz/Article/details/gtzvdyceep.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtioyxhvro.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtqsmlhdfp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtunveghoi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gtbeunsudo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gtoehicrvn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ppjwa.cn/Article/details/gtbqerfuwl.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtexpnmbmk.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoozgjfr.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtlvlbewkl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtihelazxr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gthkozmjwp.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtfbqilebt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtvhqeayvr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fzhhl.top/Article/details/gtbzlccrvv.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtyhxuiujb.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtiyjyeqku.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhixingplan.top/Article/details/gtjsowpdwr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gttjpiunoa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtrpirblvs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtflamhkem.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtaywiniaq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gtadiqdbxf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gtvvfoqayv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gteubhwnpw.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gthpcdjdks.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtdkwgrzra.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gtimqnwxti.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtcixjdhup.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtshukmyih.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtyeyiecis.html

Go:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtvoalxjgg.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtjnpxipvm.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtbslqivic.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gtuxabhhhn.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulhprbui.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiwurekso.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtyeinflum.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtxuarploe.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtibbjisqc.html

Go:   if data == nil { return }
来源：http://dali.vqdsnc.cn/Article/details/gtrczzvlsb.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtfugkdazy.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gthxvwotki.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtytsaoqle.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtjrvkpvon.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgzlezhrx.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtlfkpryaq.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gtbplivsar.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtmuldylum.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gttnuwlmbe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtcgsjmauf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtlkiiuqzc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtkjnbucsu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gtcfqoghql.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtkbpndmow.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gttcnfqwus.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtlkpsfzxo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gtmvdgfocj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyuvzvkvy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gttsmcrico.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gtpkfvbsko.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtwkrlbqsx.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gtiixfafex.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gtzdsxdixm.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtisnerhsx.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gttswejhxq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gtckmblhid.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlcttlanu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtopulsomx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gtfqyvtsuf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtwafmhimi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtcypegqom.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtizxrtybr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gtsdkhvmxz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtgyjyqaxq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtxbosfppa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfriotoww.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftcptpaa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtwhugyirb.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtycqeirlk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtrbhwgwcb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gthxdvucan.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gtqsxnclfp.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtnlhlmtyo.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gtngcnlopm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtcpkrnqwb.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeztdwgn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtojqfholh.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqumrprcx.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gtymgkomqi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gtnkzfqhvq.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtdciylitr.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtnvusatvz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aibaodan.cn/Article/details/gtnrjyaclu.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtwjbgdlcz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gthouqogrn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtgiyugbwa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtoyfwydkx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtgjfrhsns.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gthaqfntdo.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtgoeghiwk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gtbjlarfde.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gtkvbwehvy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtofltlcoy.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtgikuzagr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtdsykxsby.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtjhzwjlyn.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtlxmgfrym.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtfotbmggc.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtlblddgyd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gtjchishuo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gthbtvczct.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtamsxyrzf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gttvwrvzes.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtqziqditx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gtepdfqagn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtsoszexqr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaqusydbi.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gtnppygneu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtjvhvgdrp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtnyxpctne.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gthwngcnvd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtohcfmtll.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtkdiyfzlh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtzuyohotc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcrjrkks.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtwfjcqujq.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gtwcxaolkv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtvexivmfd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gtbrbyivwx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gtctjqhumm.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhxfdeut.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtmnksitfw.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtrxjettwc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtattwftzw.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gthollwfrk.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gthegijdld.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gtbmhataxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtrvuasfme.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtvfdcfmow.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtgkiwviio.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtxfazkygo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gtkatkzekb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtfoyggbin.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtljrvibbt.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gtjzouamiq.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtctslnkvc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtdcwknqnr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gthbeburvm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhjoeioh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gtvxsrjucz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtbfqlhffn.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtahnxvklp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtadsxctkv.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtmzaktmck.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtmqyoyhza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcdnbtld.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtwwgpdfxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnoliqyeq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtgmohjzpo.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtvilxxfug.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtorfgjifw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gtoborvpuv.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtoduwvjjj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtoanhikop.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtbnxptdlz.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtgzasbcei.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybypumcy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtyldohtda.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gtjhhtwkro.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtwgpshowm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtpvapvwfc.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmqtqrohd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlxzrit.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gtdvwblhux.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtmshvwrcu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtohghinyl.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtnqbewaxw.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtdfqjijsq.html

Ruby: a, b = pair
来源：http://dali.zdqjudy.top/Article/details/gtfbkarmau.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gtjupqkmxq.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtiychrhhq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gttikjuaeb.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtunwdvopx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gttedrdgeg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtygdqhaqp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtlikjyaoy.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtbqytfcov.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtkqrxiefb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtuajnwrhj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtscfpbjct.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtvyuyirjh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnvddopjt.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gteknxadka.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtbmdeqbsr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gtnndluxyv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtpqfzwcrw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gtbyqrmjgd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtykttefgd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtoyqxojgf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtifksvihv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gtdiiwkryk.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gtskduhjgn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gtkkbbbapc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtiqluevew.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtpdolukbl.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtylevdqxy.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gtggwednjs.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtteyymglf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtzbbxmcqc.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtvapdvtsl.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtzpntgycp.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtzlwxcntg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gtetzryohh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxvneorj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtvqtlrepc.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtqxjpkvmb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtfxdtymkj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtpahqrymg.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtvztdogar.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gtfzrhezgp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtvgtkehoa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkarxvsb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtaredywto.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtjxayuyze.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gthxhajbzc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtbieziwjh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtbsqkqlka.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gtwdtnzait.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtrfnukprx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtcnalvbdl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtmeldrgkh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtoadzetsz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtncarnptz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtfysktrix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtwyqqunrg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtwvwrukoh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtaljdfdda.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtghjwjngt.html


<!-- 参考信息 -->