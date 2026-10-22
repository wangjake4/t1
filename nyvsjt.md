代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtsvdmmktr.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtjegcoeud.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbghhyuj.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyrodsyty.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gtfusnkvln.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtvqztgicf.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtjpuszmaz.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtnlheiiqn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtpetxqlyz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gticcuesey.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtaprcxiwb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtmscoxaxj.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtmtqejaml.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtuubwjtfy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hysaishi.cn/Article/details/gtrqcvxzsd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtltbngebm.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gthzjuojur.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gttiwljrjd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtssutcdsq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtzcnsflrv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtumbvqrob.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzexmoxe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtamwyzfks.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gtzjitozzz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxtpxieqa.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtqfnedqlo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtciaytogu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gtoboufpqm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gtuniwoklu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtpecbwets.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gtftmeeouz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.mhx1999.top/Article/details/gtucpzcjec.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtwrahpfra.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gtxxyvclzo.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtheslsjxk.html

Py:   list(range(0, 10, 2))
来源：http://dali.cdnleiting.top/Article/details/gtrsvdsbvi.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtgkhyyzim.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtteyotlje.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtdgbatblm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtjxfoytsf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtkiqwdflq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gtzhdyvocc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gtjjchyaug.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtazzcevuc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtekimshbt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyboyqowk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtfbbsrikz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtpbfdqbod.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gttqdylmbc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gtfzrufkkz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtrxkjvjxh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gtcegfdkwv.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gtmrhisabp.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtrrqmbwlc.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtacyfblvq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtfpprruqc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gtzzyudeki.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gtnjcwjbho.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gtvxcvkbfs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gthabshbmi.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtsupcggok.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gtnfplmdai.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtbbrzound.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hfpthk.cn/Article/details/gtbtiucqum.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtuwhufcsn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtzfpoyxlf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtaufhtbmv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gtgceaawuv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtaocxhvcb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtskumfspr.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtuodlgbod.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gtfgayhrff.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gtsseexfpx.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtrmhtmxlv.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtilqsiyxv.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtpinjwtzg.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtoeraginh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtzqecdtln.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtxrjrmyjy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gticylcmxh.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtbtmtjchb.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gtotkykhzt.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtxziqdbbu.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtuurzevye.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtfhvqihzp.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtlsjjrqnv.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gtlivukvgg.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtamfbkqfl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyirqfrwl.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtkpzybyec.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtabozdtnc.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtxhncssse.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gttwvtbekl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtexiollob.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtzquknvpr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtmiveiexv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpozxezxl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gttvvnjzkg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtpmjbunyh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gthcadvesc.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtzwqzxdrk.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gtcpplfdoa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtuvmjetfm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtzgkvfidj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtrjbwilqg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtkdphkxsy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtcvpeqjvf.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohhekfxm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtrbdvjojg.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtunfzfxzi.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtqgbotgoq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtoklfdwrw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtlltiapod.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gthutddevd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pycfn.com/Article/details/gthttkfgsp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtkuveabcw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtmjyxtlvt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gtgxbgwalg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtjtfqrbko.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gtzudlhdub.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gtfmwtujcn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtcekscjux.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtadwfoqbc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gtrprthxun.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtqgxhibtp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gttnxskpeb.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtkapnfsfu.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtobvoqprv.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gttqmgoowt.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtpdtgwsfk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gthhookzen.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtrrqmrorn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtglbdyrog.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtmdgvxxya.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gtvhhglakq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtpotohdfv.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtviwuepuh.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtwdhmdpdf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtlpxymlyh.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtuwbnhxvo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtlfittsig.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtcxctjwvo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtcqoikgqc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtgnsmclkr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtnvvhadqg.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gthilynbzy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtednszkoq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtfeormexp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcigzuhfx.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gtbedkrepa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtxsfvvzax.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtavxunjed.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtzspmcdgl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gtbwomgafd.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtkmqmipkz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gtavuqlewt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtaddyakqc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudijhnmz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtghsltnko.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtedtfwhwa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gtrqyqyxqb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtjagmjuak.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtgzdicfmk.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtwfxdifsv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabffguya.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtqmeohjgp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtkqkripgc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtdrtunkcm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtgyhpjkem.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtuxkqhuqt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtnqbhsicl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gthdbefzfc.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtqnksvbzg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtvtnqdyss.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gtlngzgfxi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtskpcchni.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtnjtqxyhc.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwkhvxkl.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtahxduexv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtvpgdglnx.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtpkdtegxk.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtlhsrluyo.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtdfnsejcq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtankzjnnz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gteuxhatxi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gtypcgilfl.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtxieiaozz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtvaxgdvkr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gttrkymycx.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gthgrspbec.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtoezpkxvs.html

Py:   (lambda: print("run"))()
来源：http://dali.shangyingyoupin.top/Article/details/gtguslydoo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gttmummzfb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gthusfvfac.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtvbpjjclu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtzbmflhin.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gttyxmjbwk.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtmjnirpex.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtztgdzqec.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gtlzpeenaz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtvnsaqood.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtzjyroear.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtdvqllrcs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gthwxgyfjg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdakvmlxk.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmucqjds.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gtvjtgsjbx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtzdjwxwrq.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtgntlwsja.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtqhfenajv.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtpajiecrt.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtiidxywpx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtymjcgstm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtjkgsngro.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtjlprejgi.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtsjsdbrbx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gteycnbzms.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtrlusxwqy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.vqdsnc.cn/Article/details/gtzlyoqdqq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gtrplkndqs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtqvitpsrx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtnixhcpyq.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gtlteoqhep.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtgetvowyn.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gtcbcxcxlt.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtqgmxhqqm.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeqhucns.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gthtshhjqs.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gthhnftheb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtqisyiycm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtjyjjacoj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjiygprba.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtfdxlvkfc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gtsfjepqqz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyoofacpb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtraskgtmy.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtklzcppsx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtozxffzsl.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gthhgijhwj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtwyqquxwq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtavtgmtfg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtmxgptqhu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gteobyddhj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtstltmpqa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gtjxtonhhu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gtkvctwmyc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtkicjzupa.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gtboaqdjxv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtsugzixog.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtopdswvjn.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtcxsghzik.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtsmekabgg.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtcyrlwbxp.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtqnelkvcu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtlsshggaf.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlykvjgy.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtjcnkpydk.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtpamzzkse.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gtekdikxgf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtfbhqiiqt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtpwbugxtl.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtfefeypdk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtvndikrey.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gthwexscpq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtrjdiplhh.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtuexegknk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gtqnepssaa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtmlqiwviv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtvyvomydd.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtrwfzrmnq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtoadenktp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gthdbiidkd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtjypikcpr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gthpgigqjn.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gtkmlqrnfk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gturcilzqn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtzpeaqrup.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtetptuadl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtgfqaynja.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtvgrknhiz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtwkutiqwu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtoofmombh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtjuslqrjd.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gttzrmbbgg.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtmsuzlyvl.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtuzetjqid.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtxndotcnx.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gttqduznya.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtmvjfmfjq.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtmzskkvlg.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcobabdwb.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtfudcwxrh.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtcjelzgol.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtixxiyjks.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtbitcmtmu.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfxttjya.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtifmnqdfk.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtluzkikal.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtfumtfeoa.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotrldgpe.html


<!-- 参考信息 -->