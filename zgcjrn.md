代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2exgtoomr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljfulfwp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gt2lufkvuiq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmjxyknr.html

[B09] break 与 continue
来源：http://dali.yangfankeji.com/Article/details/gt2htatiyjs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gt2hjkjjfhc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2awgrhmnq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2ztduticg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2nqksugco.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2xcgykehi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqnxapbe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2bvehczfg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2yivgeoqc.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2bvqjsbnt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gt2auqjboua.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gt2hgvkqkgh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2qotdwemp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2eavndlet.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ymkzlkca.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gt2gahksggv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gt2nfixqozt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gt2bymbnujt.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2orfcqswr.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gt2rorpcfhh.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2cfhntbbq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2frmycltq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2zsdpnoca.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2lmuqyoog.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gt2dovxsyqz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gt2ymxjiczb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cucudq.cn/Article/details/gt2pkkmlrpi.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gt2glsonukk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gt2xhbgpmbw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gt2thfqzfvt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2wvwvphyv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2agacavhd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2eqnpeecl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gt2ifkrqotx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hfpthk.cn/Article/details/gt2lrnuaybl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gt2jypiyytk.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gt2vanskshw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gt2hkbdhjho.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gt2uqzroane.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2kwcrtlnv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2wutccjsi.html

Java: x instanceof Number
来源：http://dali.yangfankeji.com/Article/details/gt2qwnvtxbv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucbfxeua.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gt2gfgfpaym.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gt2xzlwerpm.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gt2illzzhzh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gt2eqdugbcv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stihdlqh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2naxybypl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2vmjhnety.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2scpzyydx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gt2ojambigr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gt2uwppzvva.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2olzbjlra.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gt2ewmleltz.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gt2rqnpvhci.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gt2vtxtdtqy.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2nvqwlipl.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2abvmnvty.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2juduijmc.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2spqjroep.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2vpmxztvz.html

C#:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2glxcfnsh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gt2uuqzfvvk.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gt2dsgjteky.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gt2qcuowysx.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkfucjds.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbqswyn.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2izthktxn.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gt2favfeyel.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gt2yapcldlt.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2ezudxpkw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zgahndxy.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gt2igdkzslr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ildfrkmm.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gt2sipjpiqa.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiteqbap.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2uqqrcudc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2zyyvczjo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2yinenwbv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2bblutbxs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gt2sihgaepx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gt2wpfwzqrw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2dggvpwqg.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2nytyggeo.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2whpcqnog.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxtxbafs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2wftsmoos.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2aamdwsiq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gt2odenksho.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gt2suuuzxiw.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fugdzpoa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2qkmeefem.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gt2ejwagxbm.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gt2jbrvifvp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gt2qhnujyqo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2nbcudhwp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2svmbbpja.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gt2adfjiunz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gt2bbkpcugz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhqosuos.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gt2sqwudrbd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gt2fvieooks.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gt2mfozcwml.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gt2niamyooj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2mxcmlpir.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2ixexgjfm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gt2jwvdfljp.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2cxjlxffy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2eyvmqqdz.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2icgmycyu.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2outnzult.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2neyqasfq.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gt2rmqbxgpx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2usqpvdfx.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gt2uttndnmf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gt2kljcfczt.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydfijevi.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylxcnsms.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gt2hiicfotx.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gt2ystukivq.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gt2xhwxwlma.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djpobhet.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2fqgizkgo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gt2ajvnaljl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gt2sltyubli.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2goecqdye.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gt2oyyclqei.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2lupojjkk.html

[C07] 把函数作为参数传入
来源：http://dali.xuanzx.com/Article/details/gt2yrcahxnz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eevlerwc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2xrylnnco.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gt2chgxwnkc.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suybliee.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gt2egdxqovr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhiwuduotai.top/Article/details/gt2esjoecpf.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gktdcroc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gt2hyxdaxaf.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2qszklmey.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gt2ougdrngi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgnichec.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fbcnqbhk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rfpdqxbb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gt2lmehqgag.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gt2rqkxqfbi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gt2cybtiail.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2nkjzhvcy.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gt2ayijxsvs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2noivimzl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2khczjgvz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2nzfxfvhv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gt2hnjbihgk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2kamebshs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gt2hdjwepea.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqqmwal.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gt2dywbnbus.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gt2oivuwzxs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2geteqarl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2itjdnwzz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2sghxtirm.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2kpxypsxw.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2fmktnwns.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2yfobhpbx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gt2sixrdcjw.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpwzxkew.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gt2kkinxozg.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gt2nqhrpoam.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gt2whmnxwwj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gt2dmyggmwl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2affnxpfd.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gt2ecjkuwuw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gt2bfixbivl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2gnzsttze.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gt2jlnuocyw.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2ixlqmyxw.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gt2lzoejtyj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gt2uoypdcwr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2aoadwuuq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2bjqizzcq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gt2yuoburty.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gt2zxdkpjto.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gt2vvajjbfb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gt2uanimfef.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gt2uscsfwnr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2gozdqhhw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2obvbifyh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gt2peweeupu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dppprqte.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2gkqxecam.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gt2dmwtxoer.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2eyalkawg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gt2vpmluklt.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gt2rcvrcrfz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gt2dsmpnedw.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2tudaauwr.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iktpqtef.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gt2bgbdvrbr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xchhmpmh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gt2wobmsate.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2ntpaiyvi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2yybmsilp.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gt2fzgyfwyt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gt2yonlzoyu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmklyhba.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gt2ickfmmeo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gt2gnqbzieo.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2zjqchvhz.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2zwkvpurr.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gt2comyfnwn.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2rokwxlmd.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gt2lanxqvoo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gt2sicbgyec.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2wkalevnh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gt2tcnpovoh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gt2gwqnyyrz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gt2irowzciy.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gt2pmomywxs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gt2bghbcjpm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gt2ihmsxdwk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2arbbsmhd.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gt2zlujexlf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2kufslrgc.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2zjrfkryj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gt2obionsko.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2djpcltou.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibdvvfax.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gt2slzcwfou.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgmlsidx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2eahoztje.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2rxebliov.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2rmlsfvgf.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gt2nemtlzsb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gt2smshdpwh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2xhlriixy.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gt2bxbqyqvf.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2vhjwgcae.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2rwngujvr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2wzmaijzu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gt2ofxbswvx.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2ybvgbhep.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gt2psofgjmz.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2okwlajgq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viaqyhgu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gt2vzgbnlxc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2tbhsavbr.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2bhihrbtc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gt2btjxnmmo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gt2qbskzhac.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2supfvibx.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gt2goakhnuv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gt2pthbiddu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2krxowhuj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkhnpngv.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2ebklsqht.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gt2dnzhffue.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gt2nwdkdlqt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gt2ifdlhiyd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2kmwsffje.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gt2mkjcadkz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2vslfcjwx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2eptcyjht.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqnohgaf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gt2bhculole.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2ppkjcysv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2qypxwgss.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2oxgygydu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2mnlcwgve.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2vdiojebc.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2jijmjwcq.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gt2zicktgdv.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gt2kjkmxjkk.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2msaeipaw.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gt2qfrtcgim.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2dxsdfvld.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2apabivec.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gt2horbterk.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gt2jirklqom.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2nclhhbbk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfkmlton.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2bbhyubdy.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2vqtnjwvp.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2nqnkpmqm.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gt2hsognlsa.html

Ruby: arr[1, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2lumrnmfz.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2udyqyaoh.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2hejmlxpf.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gt2kkmhytkx.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gt2eossjcsb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gt2byqbkgry.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2zjlbwgei.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2qaxggizn.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2jnoyxkcp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gt2ufvtppiz.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2yixjbhzz.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gt2galfbzlr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2wljiunsd.html


<!-- 参考信息 -->