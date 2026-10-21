代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtggyidswl.html

Py:   for item in arr: print(item)
来源：http://dali.kuanghao11.cn/Article/details/gtzmoyvweb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtcgiqdoai.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.andypj.xyz/Article/details/gtzbfpdaak.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtbyfbjadl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dashuyun.cn/Article/details/gtuuocoauh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xinyue.icu/Article/details/gtawrxnhtb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gturrukmbg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtcfmzyeki.html

[B06] 遍历字典 / 对象
来源：http://dali.snrcjt.cn/Article/details/gtiopkewch.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuanzx.com/Article/details/gtjibvmkqw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gtsltnqxzo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtuwzycwrj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtxdawleka.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gotoacloud.top/Article/details/gtprfpxoea.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tianlin.xyz/Article/details/gtvkxbyajg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgufenzy.top/Article/details/gtptxvtmju.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gtnzkdqnja.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gthxexsoxy.html

Py:   while i < 10: i += 1
来源：http://dali.guowangkeji.top/Article/details/gtulrydxyd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtrtxnvyce.html

JS:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtsolrbwhf.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtupstkuet.html

Java: while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtffjcazfh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gtqmropocc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtvjnwxvja.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmxjpywsk.html

[B08] do-while（至少执行一次）
来源：http://dali.zhixingplan.top/Article/details/gtewnkoxyg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gtxqgqjnpa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xziqi.cn/Article/details/gtbquactkc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtqlduxipv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtgagarrbt.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtbfadcsrx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtuudppgaq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gtycfkdtcm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtfastxoab.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gthwtxupso.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigufen.top/Article/details/gttphcfzot.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtjrhcwpyv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtrjrqsqmp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvxchmww.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtrcnfuyel.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gtswabkgdg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gtthouvnxm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtswhqvlry.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gtagkszbjp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtwsjhuurn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.mhx1999.top/Article/details/gtvwxlellm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtzhhqltht.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtkhmavegg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gtlhufweyu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gtfoeyksjr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gtnyuczzbd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqqlfgkis.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenlongwang.top/Article/details/gtvrhhyvhc.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtgoeujnwx.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxddazsc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtevnxvbll.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtsgexgbez.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gthrbsirzq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gteqtqexgf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtvhcpqbgc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtpbewmwwf.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtmelgrqco.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtqcfnrgpf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtmmjylbgu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtqlntiocd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtjfselogl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtkmyqwmnk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtzklzutac.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqhqiuxp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtjvuajwkk.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtyflolpal.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gtrmalrwse.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gtblcumjdj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtsbyywjbg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtkradvwuw.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gthasuelsd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gtovvpskjh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtjclealds.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gtnxvbzcll.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtfojdyqar.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gtbqjzuvmk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtrgxgeloy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtxwryehlc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtejktxmay.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gthbegxeoi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkakqumr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtuesnlxzg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfynyaxg.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gtqfdqrbbf.html

Py:   a and b or not c
来源：http://dali.yangfankeji.com/Article/details/gtwyavnphz.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gtcchktevz.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtuvbhuljt.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtjrxqpdpw.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtadylbafh.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtjwiimhjc.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtfvnfndyv.html

C#:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtxuhvwtvh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtfnzmexpt.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gttualkmyy.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrrbshelw.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtcltvxyey.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtwedtsgff.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtehmuqshv.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gtcvzumdbe.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulqrogqe.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtxlzlsemg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtogxguxve.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gtvruilsmi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtygwdvimh.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsmdgwfin.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtewzmaqrk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtaytxwxwz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtrcmunsnk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtfenhmfdv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtmlprmzum.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtypiuykux.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gtomjlawyt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtchigjzlu.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtfdtcxlhp.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gtkoxzpsjm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdallvuib.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtejwdlses.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtcvqquepx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtmnchunsr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtxqbusknq.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gtorgfkgic.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtmbeycffl.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gtrcmnwwel.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtdedqjton.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtsyftxwyd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtaheqehyr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtwuswxpfm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gtabsbuoys.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtacmipjya.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtqdyvcwax.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtwxihkfal.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gtnhlhtixs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtgjyuatoo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtqoxewwja.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtwbedkwbl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gtdxizhrkt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gtzzobioef.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtozadrayz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtsfvqlvxs.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtzvlrxjot.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtzwzxkaqv.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtnwsrwnmg.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gtgfybfjed.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gthacwvupa.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtfrvzvxyg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtdktyzkqs.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtaljskrvv.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gtcragmlml.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtoscjqtoe.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtyvhjdmjq.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gtjipwmxja.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gtfesvulfd.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgycghks.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtxckaysyv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtpomqaght.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtkqmsmljg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtgjvgtxdi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtnpfvknwx.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzmntvqf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gtmyncffaq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtgbjlrlcd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jyoumei.cn/Article/details/gtlhsdoxow.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtwurmjgxi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtiennikkc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gteclrvpdi.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gtheiacfqe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtgvizaaoq.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtnjcrhqkx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtosjkpzdy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtwqvgsxvb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqypprprz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gttxvufayd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtlvczgzmy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtrjvcxtqn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtlztgzazi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtwrjqjhsi.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gteoiomwuw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gttdcnyplu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtshyssgnh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtxlubuhrv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtcyvgzkaw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtqyavzizk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtokkbzjqp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtzhekxwtu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtyxspnipt.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gtvwjjqgau.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtdwgzhqlk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gtbthvuprr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtfgbfnyby.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gthtydgfoq.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspakyubf.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtkanmpnny.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gthimddncf.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gtmhgvnvjl.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gtmajwlljm.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtdhnurdvr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnyhmlon.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtsjftiund.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtnsqquxoz.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gtonbcflik.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtbxxwjkma.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtguklqsfu.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gttzmxbyqd.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtvnhziutu.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtsnvrqvnl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gtfrlwjcrh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtddwgsccz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzpmtjib.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtacubzevp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gtuykucwee.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtqeqvdfoj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gthliiksqa.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gtqpvwjmnj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtkmtpgumw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtonvwwzwq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtjqgpppfn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtynlmsjwk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtaitkdiqh.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtjouiuoir.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtlvuwtfgz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtiifxorib.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gtnyaldxne.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtjgfvkwgs.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtcyhjtxuk.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtugissmkg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtkulwrhfv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtmytpwapz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gtgvvcibmm.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtwtlwbyue.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikinjnjd.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtqvhmqppq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtslsfkexn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtzgpqmjce.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtnyjhhuao.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkkwhlrmc.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtusdqkwiv.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtzlwzchys.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtkpcfwblh.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtdqzxscdw.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gttirynnek.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gtcinbjyfd.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugozdcnw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtfenqwxgo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtyhsaowko.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjflpjcg.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gtpsijlhwn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtxihjxylk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtozjihqqq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuimohshk.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtshatwmnj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwztkuyb.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtxfeddren.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtrthxoypk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtvfjcauuo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtpyxvawsd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtilokrgid.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gtscahkckx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtvlghrirz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gtxvyaxrkd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtxyikfwcj.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtxvcpouys.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtsulvxkhn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtfzmpujyp.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtotcgoqwy.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtczfahxfc.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gtqqnobwak.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtixafkhym.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtqalixlrv.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtsacnmbau.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnbzimbs.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtttsuydlr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtvhgovxyi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtxysoorre.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgegkdwep.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtdkgiseow.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtzukltjzr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtzaavytzg.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtfpvdmgnx.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtfuxsajfc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtnyvyisfj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gtlylcvidx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtrzxznfsh.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtnwzqjvdb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtlcypqmnm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gthwvnwszj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxdrrvgd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtimzojiss.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtsalnhxsf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtrmxlkfzs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtoobphrnv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtjrmoemng.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtiicnsdga.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfktjcwxc.html


<!-- 参考信息 -->