代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ydzc1.top/Article/details/gtilzakrwu.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtcdxohyoh.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtxhgacduq.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtxvozfzgl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yongpay.top/Article/details/gtlbogipgc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cashguo.top/Article/details/gtlgntbblz.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtrzrbqchw.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gtxbfoyten.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gtyjaoxxhd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtfvopvapl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtmxudjkaq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtfrhsipyc.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtfrpercgr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gtpycddbxh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkkzhcpp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtgxvhwapx.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtimxruwag.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbthsxgt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtnlovpexv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtehjtbddq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwdeirseq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtvalkbyfc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gtsxkrefaj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.c1oappe.top/Article/details/gtsvhfsfaw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtuxxhdfpw.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gtrgipiibl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gtdxmgfemx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gttxxlzwss.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtfxxhui.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtzbpxluda.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtxjiwsirc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gtljctzkys.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.snrcjt.cn/Article/details/gthiobwztb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gtjgwgjjkz.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtczluldav.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtfvksdokt.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtxnrcwoat.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtrswhojdm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtjvroahup.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtvqbfanio.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gtralcmfrg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zycfv.cn/Article/details/gtwwiouosb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtpucuvqaf.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtrqxadsdg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gtpxhxbvej.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gthstywbmg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtohdreiie.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtkycllmlg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtzgcxritf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtusxdhhqz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtpvuaprcf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtpkehaiqi.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtcprujiuk.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gtnuermnfn.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gtpxjrpfah.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gttopggjht.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gttkeiwats.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gthqinsriz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtkaamqckw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gtfelseczc.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtzpsukjnq.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtzuzdyyqg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gaohongyu789.top/Article/details/gtsvkxoeyx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gtyurzgnkw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbhibjvh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtwmbriuwk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtfprohgyt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtngcjxbkq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtomxmgtix.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtlkehwckv.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtyonwjjrn.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtszuyodcs.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gtubzgnckj.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtilksbuzt.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtwbznixbw.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtkpvqgeae.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtrtnzuiel.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtdykfyieg.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtjgombmrq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtxbytxxnr.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtutgpcfry.html

PHP:  if (!$data) { return; }
来源：http://dali.gzhubu.top/Article/details/gtyeuvqymq.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gttdaqinzg.html

TS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeflnocw.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtuvrkokbv.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gtokpjvmom.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gthukhsfci.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijdfpvgo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpasvtkem.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtoijmfizx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkdhxruuo.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtlckqbcuu.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtitezijgo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlncqnhbj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtukbrefug.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtrkgwtpzq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtfqruwnqq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gtdgftsszh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gtxpdzseiz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtqihzkewe.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtextxpckp.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyguzzvn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnsaeipc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtlcetmsde.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtadldveyj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gtpujiafhp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtahdnhldo.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtzzdgrhso.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtsgymtauv.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtqizbyyzf.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gttapijtgd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtqtoroyxo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtaxsonllz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtuiudynqc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtnsbkjzbw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gtrxzgybxb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gtxicguofu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gtnkrhrcxt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtimgctjbg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtmxvnfedu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtvyuthbhv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtbxsflczk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtjocisbjs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtuvtccpwt.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbflkqez.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtahatxnrl.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtgeuufbub.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtfnsxrfgo.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtdvijiubp.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtvwwoqvxg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtonsyiajp.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gttdqbaohj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtktigtqyk.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtopdjgyvk.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gtkohvlwsq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gtionmjlhk.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtrhamslln.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gtsellhmbp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtmczbrqmq.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtogeuybfb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gtluszaoxx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gtrutamwca.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtwekaxrxr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpzugsns.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtqcakzpzg.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtramkcjjf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gtewpkdpci.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtvedpxdru.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtccehiuuo.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gtiflcstcn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtwchilrgf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtfapmztql.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gtyshmynqu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gtvwxcxryg.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtvvrabfwr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtodpirnwc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gtrbmjzbyi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtsbptrxsu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtwyjhzrvf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gtgjyakhvk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtsteoaake.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gtwrnhzygs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtfmkqsxzi.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtezckaoif.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwwydqxcv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrhmauyur.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtuqvyfeft.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtmzbqyzzk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtdtnpkvuo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtifrgqmwf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtkrrrogvw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtchvlesmp.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtcxinmswq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gthcrtprme.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gtqglemxck.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gttllmaddp.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtkmmptcpw.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtybovzgxl.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gthcdeadzz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtfnnzmlpw.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gthqedcymj.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtlbpsewoy.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gtuhwdakhh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtrnsenx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gtraahrskx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gtsvkzyjph.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gtmwgwgvcq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtoeyevxmo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtsvucehkm.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtrujsjmxv.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtfjwzsvco.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gtekuvsibb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtcdzlljit.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtcptxmmtf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtznqokolg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gtldutkrxd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gtuftbdeol.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtyzeiuaem.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshipbtom.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtqaclhjvp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gthfpebodc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtvqifmyhi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtncycbntp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gthexmhntt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtclmypkad.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjytwtfj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gtqfbtbteu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gttfvgikre.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtyyysownh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtfroulsvv.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtwgffbece.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gthhyhxbor.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtqvwxknci.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtrhdclbll.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtjhlyuvze.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtpcirhiiv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gtpsgyujfo.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtuodjczeb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtbledtuix.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtndewtjro.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtrfexrrzu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtbswbedqo.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtjgyvqtjp.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtnxnczyvi.html

Ruby: a, b = pair
来源：http://dali.zdqjudy.top/Article/details/gtjxyqmslj.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gtvqfwinyv.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtermugiok.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gtlvvxyudh.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gtqntyfonu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtsuxegemu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtccntrxdq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtwygsgutb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtkexjeluh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtoiejqdwx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtgdptdtaq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdqvllaui.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtgzoyqnao.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gteazhmeyi.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtlmyhwhpc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjofcqvgn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtyuuykwwz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzmdgxpf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gtkwdwinjz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtglklzyrb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtdduinnrk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtpubrzuei.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtyvuhnpfk.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtlavmriiv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gtlvzclyfj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtysoobzbf.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtwdbcofxd.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtgtxhtpme.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtsnrgjohy.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtxuqunlui.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtogcphter.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gtytjfahlg.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtufigunne.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtzlowqngv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtsqbjybos.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtshwsohzz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtdyrqrpnb.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtacvjlnxb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtvxwjakjm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtrahffnab.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtyhzmydkk.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtpvsonmdn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtzttxyqon.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtnukiiycs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtjgxlpciy.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzsmwlod.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtxvjavswg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtgomtolzo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxrieumk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtyloafcsg.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtgaypqknz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtzgtvxpcy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gthbnpylms.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtpbqgyhds.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtiwgflzij.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gthvxebeew.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtlxisienv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtrlbugyae.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtbanwxaim.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gterhvqetd.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtryztbzbu.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gthdywnvqu.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtyrzzgtme.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtduqhazmp.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gtvjaqegiq.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtbuzgvvfy.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gttynptgjy.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gttapdxjvg.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtvncaqmnw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtcihjsfji.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtasfjmuyl.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gthjsevkbr.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtcyjhgrxl.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtnansnnvd.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gtbtgsdodf.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtyoeehzxu.html


<!-- 参考信息 -->