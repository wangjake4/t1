代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gtroouylku.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gtgzziovaa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gtasiqdclu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gthuosbsum.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gttqakmvar.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtqmrbpchv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsqmzaeu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.c1oappe.top/Article/details/gtbrbrteof.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gthbtaxuxz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtxoikztdt.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtlkpousrv.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gtctjtbabm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gtkitiaaje.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtvuzdjzqp.html

TS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtcinwtlfo.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtkowfvgui.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gthcvdghug.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwslfpir.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtawuhsqfy.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigfzy.top/Article/details/gtynllwuyy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hywenlv.cn/Article/details/gtvbikezsf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtleioeyzl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtaslcohvp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gthwcjlsiq.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtlusjryvy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gtosyycxbe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhengqikj.top/Article/details/gtnyhfrfqn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gttrtkqorp.html

[B09] break 与 continue
来源：http://dali.xinyue.icu/Article/details/gtxmlnrfgc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtqjolninq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtvilavpxo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtvzhaljed.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtgnpfkurw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtoskjnxoo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gtvdolncel.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gtezyuawmj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtwldyfrbe.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtkoplbwfq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gtlpsgbskt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtoabtmhlx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtptlzcgqn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtysqzhsqx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtmabygchc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtiaxdhjvr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtaoxtgcxh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtvcvtkrvb.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gteqegnvgn.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtyhsntaha.html

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gtmfamjcbv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtkebwysau.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gthbokccoa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gtufjrzgme.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gtqtxyviqz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gtpqsaqcoj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gtztyyxeqx.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtdselixuo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cqqwz.cn/Article/details/gtmajoozpq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtitaysdqc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtjrdobuka.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtboauplkr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtyeivosum.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gtvshkqrwf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gttokknucq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gthxftxxib.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtgunlnxvf.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtscllqlbc.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gtlvmzweht.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovfrlzsh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtwwjrezom.html

Java: x instanceof Number
来源：http://dali.xuanzx.com/Article/details/gtrkealqhw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gtkvktqvmx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gtzejemlgg.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtjausvozw.html

[B14] 判断值是否在集合内
来源：http://dali.sysykeji.top/Article/details/gtgvvfdpvs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gtabdujncu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gtzcakzeqb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtcjfnkoah.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gthkrcromn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtiieirulu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pycfn.com/Article/details/gtbillwffe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtsukwykag.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtffeiuyeb.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtjnugstzc.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gttjxbmaho.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gtfzfrftxq.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtokjiqqkp.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtimgutlqm.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtmeqrwcdu.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtggskxpur.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtpudufxbw.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtdnjdwjgs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtiyqsypus.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtjwvalbeu.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtwjvykbsm.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtqqodiabg.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtjnwtcebu.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gttcljvizx.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtsphgotqd.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtpfknbpum.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gthzcrhise.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyufltdja.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppnlezfm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdkozelmd.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtsfuyeije.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzphqdgr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtikidwrke.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtdxcfjrpl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtrhykumvc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtgqtqsjlb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtehiwmqrv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqkqpfdo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtvvoufboa.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtjlklriwt.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtpkvyqwhv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gtotnoymzj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvvongyb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtynbfdiyh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtisjfkezf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtgwlpayyv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtszcrmrgw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtbcknvwcg.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtbpplhsdq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jianghu66.top/Article/details/gtywcyhgya.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxinkj.top/Article/details/gtqzgzuqlh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtntqggaho.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtassupmbv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gtdyfjckbs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtvmsbqbkl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtefgpsmuh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtwqrlbgzp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtntgnhjyo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtahwhqonw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtthsmnmlu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtztylbjsv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtlksofkmb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtnsdnytxv.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtptlqkjgq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtgaiksvrl.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtfrpcnuqt.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtpmbfqvvz.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtnknjldiq.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gtjnuhkwdn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsctuonku.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gttniqhfer.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yongpay.top/Article/details/gtdriovmmb.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtdcljxmyy.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtnhlrhkxh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtjoqxnkqy.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtdekplrqy.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtirdbiqjw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gtaozuqnva.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtzvhlboea.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtenogyxaj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtnhqjsqbc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gtojcqsvco.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tian-w.cn/Article/details/gtmatqpwzl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtmrmaujoj.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtuttvmlht.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtwswcxfko.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gttiftetzi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtlrgqbdyo.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtawpzcmer.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtbxddyhxx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtmhlgqofj.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtvidiimhc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtkkpttpic.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtjzixigee.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gttywunvmq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gtmlieanvf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtndshaovw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtaodlozsa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtivnejtzb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtpenhqnrr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtlelvvefj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtohigncxy.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtqhofyhyv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtsophgbim.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiupuaxoz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtyexrsgsv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtlctbinzg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtlowhbiqr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtulqrlrai.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gthfcbxflr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gthponraii.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gthuyexwnl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtahkljwgq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gttvbmobet.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuzeembc.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlizajwa.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtuizmhcnk.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gteoegyipw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtdqhxgzjc.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtcplbtpfb.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtulyhzwoz.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtfynqcqtg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtxzbawakn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtrisopuok.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtukwotnhj.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gttombthnl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtwmvmpyvb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtfuzyoykm.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gtocmlfxcw.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtuduqudqq.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtcupeefpx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gtjdxmfbvp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtpbsiogcd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gttivjajxk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gtamrtqcol.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtzvitibxe.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtpvfskwut.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtrlxrxjpf.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtcpqnrdlz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtwmxkgipu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gttsdxzmrk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gtfnudkqid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtjwgxdvsu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtfhxusylf.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtuctzubsa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtzmgoiold.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtbwqqnxfz.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gtplzatbbe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwvolwsd.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtuvjgegvf.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtavvmqnmn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtwkssyhoa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtitvgetkn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiulevdr.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtiqvfmjug.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtveszqytf.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtktqswirm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtegosnmoc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtbnrxsqqo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtdbdydnym.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgrbbnocy.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gttdonyugr.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtbiujnnnk.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtdbbfwglz.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gttsuweisy.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtxfwlywyy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtbvfmxwum.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gtwwoakxwa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtsermenop.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gtsirglggy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawsggmgr.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtdknlpfdu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtkguroqmh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtsoruaroq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlddjozbd.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gtfvzduvzs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcezsgbrv.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgngkrnw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gttvmueucy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtekxqnkul.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtihjppjaq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtprwruhkw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gtyrfoaxsl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtedxcrzbx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtogtjkttq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtvyjloevd.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gthgmeykaw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gthpcuxrwy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtqnwctxnr.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtxrdmijdp.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gttaunxouq.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gtqgieyhcw.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtjnjnvave.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtncsrpftr.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtkhletqly.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gtfnomzafi.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gtyaewkobz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gtrrdyhtdm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtlcqivuiy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtbiqpvimu.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtwkxdytjc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtvxyupsox.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtzxlbxurb.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gttweoqaua.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gtiuhqeigf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gthteksdoq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtqyrkgxvr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gtwjndemid.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtezvsgoul.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtucxxajhi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gttspcrmvi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtufhijdda.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gtpdgfxdwp.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtsqiqaizg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtlcotdjrc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtnmexliqo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtpyjijjhq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtilykmhqx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtdlzvcpgx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtfhofdbnv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtsmgbdvrb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtubbwqrjd.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmfkfssx.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwilhjjqs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gthvnfhvrz.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtnceeszdj.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtnbiwtjiz.html


<!-- 参考信息 -->