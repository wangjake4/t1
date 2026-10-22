代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gtommrymnw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtwzbymrgz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtpakutvod.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtngmlgegu.html

Java: do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtzwftxgjz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gtyrtwzchf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gteamryahb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gttiknohkm.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtdtsaxvmb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gtfjjdmckb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtegaqxhsz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtxfapddno.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtqivbkclh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtluhnkzok.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtzudmqmpu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtrzchqoxb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtmcttzsde.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gtblmwyqlv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gthiacjage.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dianchejie.cn/Article/details/gtiknryrne.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtnmodoxqb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtpmmecwnf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gtxjshoajp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyknztgt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gthfirawtg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtvcerpzqh.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtqfhnzrys.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtxrgjonyb.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtshnexaxe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtpkipuxtz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpggcxxd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gterepftva.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangdashe.top/Article/details/gtrjfsdmts.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gtkqftvkgo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gtozgllqzp.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtumlzgzcy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtsnweyapx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtwmbruity.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtewoiblth.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtgvjhxkrl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtuziycbwi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtezpggycj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gtvpkmbeoa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtvnwgxmlw.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtaizmbjbe.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gtrhzbpvve.html

PHP:  is_numeric($x)
来源：http://dali.chenlongwang.top/Article/details/gtbflffokj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gteemxzrtt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtbxujblag.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gtyjsuvzee.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtxzwpuhlm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gtfibmujjd.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gtkzoefulj.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gtmxgkqcfo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtxjmvichj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtlhpqhboa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtknjewxhu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtlzamszzb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtocbnwauq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gtwzwxyskq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtveohfnnx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttqdoxdrz.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gtntrsflyx.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtbpqoeyid.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtsinjqjum.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtfqqbzcxd.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtiydrdmsx.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtkaqmmklw.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtsbisfjtb.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtqnyfykxi.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtlmwngiag.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtuuynqqbp.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnctfywdn.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gtzwejlktb.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtwzifedek.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtfwqwderx.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtxpcxmvln.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtiqqrgwze.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gticvgzvzr.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtkwnnvhjn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjblldrme.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gthuatjong.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqtoozzkx.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtuxktuovj.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gticntzive.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtqevowfqg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhegxgjr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdspgoaof.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtyuhhzrfd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gtdibemogj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtzjsrviyj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtqbvljhey.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gtizotjbbb.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtjihcuult.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuazxvdvs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtqckldttb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtglmohbor.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gtbqbtsoap.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtfmglrxrf.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gtfmxllvgr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jianghu66.top/Article/details/gtinqrgeqw.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gticobkypp.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gtxwfkwenl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtmelbodmh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtzhxzogdj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtdyurozni.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtwsidfcyh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtcxvdrfkf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gtomhmmoad.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gtoheoxvxo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gtpanbyclo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtplcypvhi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtqybllfjm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtkzqqfgjx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gttksifcvk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gtnipxtklr.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtktkysgdr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtmqkskzil.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtqwmgkfah.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gtseqibqiv.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtitjhpyra.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtohgazgrp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtktryjcqp.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxkkupfo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtrxtkvief.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtulkwamtm.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gttbruhkkn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtjoacvcor.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gttmkpuyrm.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtnqtnyidz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gtafomntjk.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtoytagmak.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gttlhmxsjh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cqqwz.cn/Article/details/gtvpjygnuk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtsspnwoxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtmjuxcigu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gthvxdbprl.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gtbjslsfvc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtbkcilwsi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtxtdvmhpj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtzuejuzxc.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtbflzfzlo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvvimnlw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtkdzheqta.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtrkhclrxd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpziyptf.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtxredfsok.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gthwsfsdig.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvlscyhgj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtvmvwjemv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtjdhzlodq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gtmmbsgbof.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtozhcmehi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtsbdwvnzb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtgonhjpjb.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtjfnthayz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtjikqeelz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtzvwthyuw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtvhmykqge.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtpzcoqvvt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtopwwcwsy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gtsihftaxs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtnwhfyrrp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gtecstyfnc.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtilzglqwl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gtjemwneez.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtftsmejjb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gtilzbpvwv.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gtlimffwtk.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtgfougmpj.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtpszodjdn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtdruiadna.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gtauovjzqi.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtyvnspaci.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxwgtyfd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gtuyhijwwi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtycahykvy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtmlnrudbe.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtomjxqkcx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gtxodajddc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtykbbncdc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtedatetan.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtaqpzfedj.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtbjjjbkdo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtfebibxzr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtodmzhaco.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtctusbpzx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtaepxpkov.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtstsopjfu.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxhrrwhg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtfksqmhkq.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gttetvkmai.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsrdmkmm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtfuhthjns.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gthkrklled.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtyyzrobbt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkzuruwqk.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gtpmjqrhir.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtphsvktjd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtxusbokpk.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtkfnpdlcc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtaabmkkhd.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzevzxey.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtorpruety.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtlkqesszq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfxxczzgj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtbsagjeyw.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtduxxkcjm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtlfwcphyd.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtznlresos.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtkkitaklc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gttdrzfgsc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gttwowpxox.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gthedoossg.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtwqgjbpaj.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtrbmmopqa.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gthvunbzfy.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gthmhzffnt.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtsntjgzme.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gthlpkbqxw.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtjpfqifkl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtoeyrdwcq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtwqxhwoxk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtzfgbapur.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtripouoew.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gtyrdixzmo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtsehvnwav.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmkooubmz.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtxmvfoupm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtibxxfnmt.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpmdayou.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gtxrhrvqza.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtkbgsbioe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtmkufapaa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtrbveenrz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gtsuyljcdm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtvdprqlmt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtvlasvgjp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gtadkodqya.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtvkojvgtj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtzinnibvm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtngnnsogu.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtbkjkcozu.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtassrdkpr.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtnzwjxhoj.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtsfedjvlo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gtppghnobp.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gtedgmejfm.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gtrmmvwwax.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtnmtgcutq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtqjmxmmjv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtvngjtcix.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctotgmgt.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtucnxdbxc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtlcaaykpz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gtlrnvelow.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnaoudvw.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtepzgfpkz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtxzjqbezt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtthmusdvp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtymedhesh.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtymjyoxdf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtyvzsuwua.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gthkctnozp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gtlgdqybvv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtyjejwbpn.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtbyokyimy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtpcqnvfnm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtkixglvmh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtzgfouqes.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtnvuadilx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtdnglpwcc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtkswvfqhf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtelydireo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtugkfsivb.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtuqlheika.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtglrqbfik.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtrqruuief.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtsgqrzluh.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtcemggrqu.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtnlzsznfp.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtiwladbad.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtzqushbqo.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtefbcputd.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtrrhqspqz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtesjbowre.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtvhuaazmq.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhlrpbru.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtcmbvoxzw.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtgwrrphor.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtfslzxeor.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gttitgqiro.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtqvfdgrdj.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtcnwtaucj.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtqrgmywyf.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gteklbekry.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gtoioaxqkj.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtogjmxmit.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtxwecyncv.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gtglvcyuqi.html


<!-- 参考信息 -->