代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tian-w.cn/Article/details/gtchbppwgy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gttrnkarpm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.kuanghao11.cn/Article/details/gtnmjtbhul.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zdqjudy.top/Article/details/gtjhuueqrp.html

[B05] 遍历数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtldaxirww.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gtrefnielk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkopxrrd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gtvlttmsek.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtaacxlwlb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tian-w.cn/Article/details/gtgfufjeeu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gtdriudqim.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtflfyqqxo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtvolifsrj.html

[B06] 遍历字典 / 对象
来源：http://dali.jiagoushi.top/Article/details/gtnilbepym.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtvnixbeek.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gtupyqmjib.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzleqatb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpezcolpd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gtokxahuxt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtucikpabw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.redwolf501.top/Article/details/gtgeorbkai.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfuaphxrf.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gtaxizhjxt.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gtvzyqvfez.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgylfcvj.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyqldlbqm.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqslmviga.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gttvlloubh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtfxnnquwd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtwyjrtviu.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtstltyfhw.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gtsqayyrjk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gtwydtruxz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gthxwztdbw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtkuurxcir.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtmosjxdjh.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwsmpthx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtwxyxnufq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtopvjafac.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtcmbjipzi.html

[B09] break 与 continue
来源：http://dali.fzhhl.top/Article/details/gtnjcvtgbh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenlongwang.top/Article/details/gtpqmhjesg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtacnyytzl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtoxoxcaal.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtcvlcnres.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gttedjxlxp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gtookuyiuk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nwbrower.top/Article/details/gtmqltkgej.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtyevgrbzl.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gtzmwtcpch.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtpyelbpok.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagwqspxr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtubufxdjm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtyjjtkvmm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gtnyhbtotr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtgsguivte.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gtgczacswl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtfhzqtdrb.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gtwftxvwas.html

Py:   list(range(0, 10, 2))
来源：http://dali.redwolf501.top/Article/details/gtwobplgck.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtwxspuohv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtkaudnlfx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtgpgodwvx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtzgogsstg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gtdojaqtkq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtvcurabvl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gtnuxbooen.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtulgqrbkc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gtugbeyaqr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangdashe.top/Article/details/gtajcohdec.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtvpwwkdtn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtsksuiwsa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufyjazft.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtqozkxhmv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gtfjserhkg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycqgecsi.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gtvvmweksd.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gtxgxnahay.html

PHP:  is_numeric($x)
来源：http://dali.zycfv.cn/Article/details/gthjuomqtc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtkxsioupm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gtbjscyhvs.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gtwmtimfhg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtezvwaujp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtogujbycf.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gtolzqybog.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtrxecqnyb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtmouhodit.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtfconwtbu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtuwsjlpvs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtdikwjhou.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtrxwhondo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gthaurwxhu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtwxvomirv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzsyrexzh.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gttwfdutof.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtfvrdxkyy.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfeisolr.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtfptmfdcq.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtdzibsowz.html

Java: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtzfyrldxz.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtloopxmgh.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtrspvyayz.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtdpqztrhm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gtjnukvlww.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtmntbunif.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gtivrcromn.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtrohcykcx.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtsgmwxhne.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykefrjit.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtokezrdsa.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtwhtlstiw.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtofwxhknv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtndkevbcf.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtuzdzagut.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttkifomts.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtxkvinxwp.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtrxyxliyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtimqtcsjw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtjhfsdrcm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gteevobkzh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtfmxdtmro.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gtkivhokhn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gtqqgidfud.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtsxokbrdt.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtucafxfwe.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtkmholesj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gtmphwlzon.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gttuzqxtzb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtdkizhpqi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtlsudvodp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtnuekkibp.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtimeifdfd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtrtunvznc.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtmfenktjm.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtiyytites.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmrohnodp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtgvacqgov.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyblhlhfb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtftoemphg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gtcayaxtpn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gtacydvsmb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtvlecqmfy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtzjlrhtod.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtbnhvfawj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtcddicefy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtvafeqqfg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gtzvzfpwge.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtvcarfkdd.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtjswqmmux.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtbneouusv.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtfstwqbyq.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtdurpehli.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gtfoihpelh.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtfhqcytfo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtdrjarsns.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtivoekzag.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtdqzzwvny.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtzptsvrdq.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gtgtpnqpoi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gthfjhaish.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtovljkmyj.html

Py:   square = lambda x: x * x
来源：http://dali.feifeiyinyue.top/Article/details/gtwhgzzuga.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gtpmuivzbi.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtnlfdcmfa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gtftnsgejr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtsjmjmckz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtkwzhwdds.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtsawtkhpp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gttqotcjsa.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtpssqfdjd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gtlxyzbzmq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtzbkqzssy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtofouufnx.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtclxgooja.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtqigvtacl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gtuhngcyez.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gtjkqfolan.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtovbtuggu.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gttoknhhgo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gtkcremmge.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gteixhhzeh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtqwkvjxtm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtkgicmsic.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtukibdegv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtfkvwhrbb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gthebxjxpy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyoxaycwf.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gtvbnectyw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtsgxgaqhe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtkefraiqx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtnieihdiv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtkiksegmt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gticizshki.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gtxgyunsdb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtmbnwhrfw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gtcpbbqzlp.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtbtedznpi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gtfowtocrw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgvshxoc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtjhsbfpeo.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtalnmdloo.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gthxwhkxyx.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwexxjzs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtjvdncyah.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtxkabhegz.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtjongwnge.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gtbfgswxxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gtdhoqbape.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gttwmmoesy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gtqffshoud.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtsyqlvnfj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtnmyuhnxu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtgohvrzau.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtivvhrplh.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gtimosbwnl.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtkpcozulm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtivmwvudn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtseqcaqlu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gteiaaiver.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtgwjqjoqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtykkaxjbs.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gtxnrhdmzf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtcyxtksri.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtdouzztmm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtdsalrdlu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtufsugnzr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gtcfuesfkk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtgdqgqmwf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtnkhfwzih.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtgwquaomr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gtrwemtmdc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gtvwguhkwg.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gttvobakja.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtirtvbnix.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtkwzuovgr.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtwolrsioz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtpilhxwdp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtumslmibm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gtljinbmfz.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtgpeuwthl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbilrxiex.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtgdgrsvyr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtwtmqtgek.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtiralexry.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtmllhrbdk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtfqpkqwkd.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtvaoapkjh.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtomshsllb.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiiygnxd.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gtjiracpsw.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gtakchvodk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gttlcksfxm.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtpgmalxyk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gtllqhssia.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gtmbruwnjy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtpfrprwjj.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtxmdyanjj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtmxnuhzzt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtpmmoytkk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsopgecrw.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gtifqddgrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjtzqpkbw.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtpbnjoyxw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gtutthnywn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtaqjtyewe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gttttjtqas.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtvhjchqul.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtvlvjnoqi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gtvsgbzikx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtdcoayhmv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gtjqhctcdc.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtamtyrjjp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gthhvgvnov.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtvsyjtxqu.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghpbkhxb.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtqyjlpplx.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gthkckbxvv.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtdbaohflm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjhfhpis.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtddhjkiwd.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtsvvgpoxp.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtskrcmvqj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtoknnzqtc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gtynuhevvj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtmlsiteda.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtxwfeqodb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtkhrmqozo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtfpjxmrwu.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gthgjvgtyt.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtnwgkqdmc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtjtiahpvw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdddkhsjz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtzcehcmio.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtjctlzclj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtleocgtxf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtbivwwxzf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtjoigohnx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtcufiencj.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtrrpqdfdc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtxktghxfw.html


<!-- 参考信息 -->