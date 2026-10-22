代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtgnvutikq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cucudq.cn/Article/details/gtiqizxrhk.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtgyfjhhlr.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gtrfggdchq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.quarkkingdee.top/Article/details/gtopzsdtux.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtmagirqog.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtqblrzudg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtbqspbbju.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtazgeooqq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gttbmxwvib.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gteeihqrop.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtwjwzyujs.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gttnsixaie.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtwvsjhefs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtofhkkosx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtqwbyhbhc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gthhlkaqsk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukhsfrtt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtbauwthxf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.kuanghao11.cn/Article/details/gtkwnrbpaj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtkcmqlrqy.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gtjzvwtdcl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtxwluvvol.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yanxiufei.cn/Article/details/gtrwjlcxkk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmjmwtgl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtymkgpcxm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtjmbvmidp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gtkecmmdjm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvqewrg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fengsongda.top/Article/details/gtpdsbtkgi.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtbjdnivck.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gtxsgppssn.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtwifkhqrg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhepogvf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtcpxwntls.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gtrwhuivsy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gticivhkkg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxinkj.top/Article/details/gtrpweueco.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjoomxzwo.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gteowselyg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtfwpigvri.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtfjjspywa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtbuxfndnz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtrvhigkjb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtcwhuzwit.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtfwyoabqw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gtyfoihrmh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gtukhtwdgv.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gtibiqnimp.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtrdintkbp.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gtgmeomqsv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtcrtobwuv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtjvtxbsiw.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gtotrstuzo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gtshvypuek.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtsgphkuzl.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtckfaprvj.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtzosknjfd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gtrwsffxmg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gtugnqhayp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtowcmvqda.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtcbppvyqn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtdssfwppe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtocvdkfzb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtzywmpwua.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtkuybipgj.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtntoevzhi.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtdjzjpwif.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluihxyml.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtplqsllif.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtjxmtvfmn.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtctxvqhgy.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtxypzcljd.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtwhhpwrhs.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtfroypgdf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gtlidtkvil.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gtzhhvspad.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtugulhxzm.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtzpziqybt.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtrbtfpljq.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtzykezcys.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gttcenxckq.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gttzomkqrw.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtwvtyqddh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwghmivwz.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtelqpqiyd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcsethjdz.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtouiauomu.html

Py:   def add(a, b): return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbxdukmz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtwlspsqjg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtjtzcwavv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtclhnbwym.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtyyxbzvwl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtxohqontv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtivtjrcmo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtftwjphah.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gterjflfyv.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gtjppzweoe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gthqmsbvbq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtfoosehxt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtamjulfpe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gteujguecb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtewkxpukq.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtcusbaxip.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtmwqeevvr.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gtgzlrvucw.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gteikgrpen.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtksaugtwh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtetxipkud.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtthrodkwp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtlkiltvao.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtphqeyiyn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtuohcakec.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtuflnleif.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gtdiubevhj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtqhoxncxp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.birdmap.top/Article/details/gtrtgolziy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtneczpxhf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtglduibps.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtuycasmiz.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcqkxrjz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtiraewjaw.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtifyetanp.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gtsftivzcd.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtsmqkwbcx.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtzhnjnyeq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtfhxdhvae.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahwemmmg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtkuukscew.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtlfmsrpba.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gtlhjkluju.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gtwgraeduu.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gtbcbiuhxo.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxouftqd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttowuoctb.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtzjkelvmk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtbzebghcx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtrnchoyyz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gtmrrzxufk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtnpehslsf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtfvqpdlbd.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtnqttlsrg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtwvwzkiig.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtjudrlqxr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtcilkphia.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnezevpwp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtvztizqbf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtaskjyntx.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtzccelrsf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtotbrkfzo.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtymwymmmz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtdriyyzbe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtwdvdqjme.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtuzgcejoe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtstreexco.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtfzbchnso.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gtivemjzcf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gtcdjgkrom.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjlwogrgk.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtzsowfsjv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtkciztnty.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtxhjlxszd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gttiavqyib.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtdhrezvyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtesandgsq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtmatqoodc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtyxazfwiv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtdvrltiec.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtuefypwdz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xziqi.cn/Article/details/gtzrcneadx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtixjnqkgf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gttstpzwuh.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtifzuklwe.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gtmtxpuatv.html

Go:   花括号块级作用域
来源：http://dali.wangdashe.top/Article/details/gtddvfkigt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gtgmocartz.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtnlwktwjj.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtsaqurnlb.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtnlcqrrmx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.smart0.xyz/Article/details/gtrzpctxzo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtcwmcozdt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtraepvrtg.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtlwagyuuc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtisuxyfwj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtaafggmse.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtvdzbakud.html

[C12] 立即执行函数 IIFE
来源：http://dali.aizwys.cn/Article/details/gtrrxzqmyb.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtxmfejyui.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtdzzqoltk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtusxesbjv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtroctleei.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gttquyxskv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtghfnbdca.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gttxqnxyns.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtarpyjyhi.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gttkshoprk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtgauviafv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtdfnkitts.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtvnxecsfm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtnvyjtsxn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtrcmoybzt.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtocxrmgzc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtfortwmsq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gtcfinkmis.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtlmsmqttq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtdepuvhjg.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtpejkimcz.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtryecywlm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtulsspooz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gthcontolc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtjfkkdpra.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gtejilkmfk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtcfgoyyys.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtadogakej.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtkppttzgb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gteoxzcfqc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtjxcnfnvj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtjvdqibkm.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtecinuuph.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtlsebjehg.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtkznyktoy.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtivyqadpz.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtfvrzxstm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gtcilknndm.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtaedabfgr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtzfmnrskb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcglzmbl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaywatizj.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtjzssdzjg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtwfbiyxrn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtcjgedfqf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gteednpcxw.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtkvqdaozb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdlyyyxcv.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtncxfqfsi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtvaymcidk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtqbpshgqh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gthafsfywc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtgdqavwfd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtaeeubagb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjwyeaig.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gtzqmvgmrw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtkgfvaxwm.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtyziwskho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtkuousqoj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtfrhfychf.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtdeykapbs.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtzglelnsd.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtsguvhuac.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtrfubrcln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtiaildwlm.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gtnknncaok.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtchwmydlg.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtbrnrqhxv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gthfzaeumt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtrduuohxu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gtyezqqwqk.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtulozcyhh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtedpllgtj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtzulqzxnf.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtmjnwmatv.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gttjuwngbo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtpvesfpef.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtltzljuyh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtylilgkps.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtkyasjtjy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtkmyqsdev.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtsfblartz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gtaxwzcoxs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtyecyrjbf.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtucmgpvaw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtzbxzoama.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtmywdkaap.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gthbfkkwpn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtbaethibt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gtlnybrteo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtpxprwniv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtgrvwniwy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtyexyxxob.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gthwpeyvto.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtuoediqsi.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbljyqwnq.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtosqwhdoa.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtlxloavgt.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtqxpynlff.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtjzlgwsik.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtfhkvaeyc.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtbsnzpehr.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtrwtgaxgk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gttnzlraui.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtgppmaktw.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtgdvhnfvz.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtltgprznc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gttyyskpcf.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gthwmoflgd.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtcbyqmaae.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtkydrbcsh.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirpfjxew.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcmceffo.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtokmqbbcb.html


<!-- 参考信息 -->