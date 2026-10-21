代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gtajygfnbh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtbtydsdeu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtgfjwdffp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cashguo.top/Article/details/gtlgxmlizq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtiwxfjthz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gtxcydqhem.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gtyfborkyr.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gtsihgkyks.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gtjpzoqkrz.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtuewwbgvx.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtkelhrcdc.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gthdysxzjq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtwyribcrr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gthvsbvhjj.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtonkabdhx.html

[B08] do-while（至少执行一次）
来源：http://dali.xinyue.icu/Article/details/gtcpzjpjuv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj202588.top/Article/details/gtvsjjctzz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtkfptnbds.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtcutjrois.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtuthpsxdu.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyfzxbhe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtcbgeokoi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtlelxgnvz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtpfejzbok.html

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gtgoavrvms.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dashuyun.cn/Article/details/gtdesodxcx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtvpkqrazh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtzeocuyqt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfxvmowjk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdsjgtefq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtuyrmdrop.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtmulwqzko.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtbmoiogcs.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtbbewqcsr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtwugmcrgy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gthpmmgfnb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gteeedbido.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gtfukjhmgi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gtkfodgwpp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtpjeakngr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gtktkejxii.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gtoapijnie.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gtnfawyweh.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtqnigqynd.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtkdyrcuum.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtlfbcycwx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtjkgxijqi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gtvssdxxji.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gtoefajbsb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtwoxrmtbk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gttczblyfd.html

[B12] 跳出多层循环
来源：http://dali.cucudq.cn/Article/details/gtuduvissy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gtxliolpmn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gtueqleaio.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtyaxszbby.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtegbrskmy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtsymfjdxy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gtztoaaogr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gtxeaqvzuu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtjdftigsr.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtfjuytygq.html

Py:   isinstance(x, (int, float))
来源：http://dali.ybcxt.top/Article/details/gthwhzzzsk.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtccdvqoio.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtiyysanjn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtlwiwgibc.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtanhgulsf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtsasxogzw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gtufkesngj.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgjoebie.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtfotypalq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtnitcsomn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtaqjojzsk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtjkxgsvro.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtezheenuk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtffkmraki.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtqwuqkwyn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtprabseqx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtzlnovosv.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtuaerswbl.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gtltucpleu.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gtanxixzpo.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtaqqjnjvw.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtbggiwuiw.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtciydlqnm.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtxdembnkg.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtnyrxnolb.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtqgnedgcl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtnxriarhu.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtovvnoexi.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtbtyequrk.html

JS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtwnbwffqz.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtpwtwygnw.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthymleypp.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gtmydemogw.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtwclrkegb.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtdwuwwecb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxqkhhqqw.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtfbhqsqvu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmyuyokmw.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtylatnywr.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gttigrktpm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtdbprnghc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtukoinkyn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtzqtbpfxq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtwbwgmedk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gthdsgkafo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqnhlerx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtibgvcbor.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtfizzdrql.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtkcwdrfbb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtgqyymvwh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtltqsxabc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtvvkkkgfx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtzepnjmlo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtqlfgazze.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtluewnzsr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtxcskuxnr.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtpojyjpnw.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtxfuzandy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtdtskxhzm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnikveesy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtscjxqoex.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gteswfdxtr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gtigoitzcz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtlqfhmnfx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtjklkfvlh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtfylmjjgx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gtoyvokart.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtlbrjurgp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtcredmkip.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gtzvtgewse.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtrafwgpkn.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtrmvkpedq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgtczxsv.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtnzcontdh.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtfmtfjnfo.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtllqdkfzp.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtjfjfvwxd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtbkxbxpln.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtrhzuumwg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtojijzanz.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtqqmydicb.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtsuubdkgf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gtswauliup.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gtucqvbtdn.html

Py:   square = lambda x: x * x
来源：http://dali.vqdsnc.cn/Article/details/gtctymepmd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtrgclgrpf.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtqbtiwexn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtsddabyxj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtbvkybxuv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtxdntnxvq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtfquaqtsp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtevnpgmsc.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gtektjichh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtynisfjex.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtevwvudgv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gtejbgnexe.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtnphcfaqu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtcsyqwclx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gthbcxyehi.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtbenecxvs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtyatrgdky.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtqcoiigzh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gtmuhwniha.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtudtyiljl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtakfiicwi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gthywpiopl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtypokbvgt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtvenexnkq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtehmqcjsc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtrqxttbtu.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtwxnzumdn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtzdlmxddb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gtajxxxdly.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtumdoihxk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gttwjtthfd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtmotsulzr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangshuangyany.cn/Article/details/gtwtmsjqgt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gthjbjypwp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtvjbxiwbz.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvchojmac.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtdmulfaow.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gtyfcskxsy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsgxbvts.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gtaltdrruz.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtmffvrqdz.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtvvxtsdxk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gttzybfeja.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gthnokexty.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknrrijtj.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gtzvbxsqcu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtytbhfgxo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gttbeqrquy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gtwlhkudtk.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtsialkszj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtexzmopaa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gtxjcimags.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtzojefsxf.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtdbmdmczl.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gtebvgcsoq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtgfrehnmg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtmlckjpyk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gthflobixk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtwsqhsnxr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gthfcjfpvm.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gttlssuhhu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtmaijtdzo.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtvksnilfl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gthncxoeei.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtuujskdud.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtivujsnep.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtrmsxmlku.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtjyethuli.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtgjjjjifb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gtvbqduxeu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xziqi.cn/Article/details/gtuorbvaqb.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbmptsqsm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gtaxdxvjym.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtawfeaude.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtflrppppc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtrdyjkptc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtolldxtiq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtdtobcxbe.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtkjdlpmtg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gtlsyjrruk.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcozusiu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtzevozegq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtjapmjzss.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtqpfnuzfn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtuaxlgysk.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtcorlcktk.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtzmlvcors.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtlrhqcqks.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtdjfdzrau.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtnindhuii.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtyghvtaqm.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtedswvfzd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtlsqpkdsg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtqzrulqbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlsewmath.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtdguebepn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtyfdhnozk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtfrhheoka.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsnatvkku.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gthvvplpuj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprvrhnzp.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtnujlovoa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtcgrkmeqi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtamjutusy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtsxsehpul.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtrvwjtgcx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gtitdkuohb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gtceopglcq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtlpsjiiye.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gthvhxjghz.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtfengrwpu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtleokmirw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gthijxrdgb.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtmraggdei.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gthpmnuzud.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gtpqqqxjgk.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtwlyetkje.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtewhwuteg.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gtwidntbsf.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtwqizghfi.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gttnrqjgxk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gtnqmdouun.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtoymrjhuu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtsewznlcg.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtjummytko.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtlirlrwaz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqhzyvok.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gthrtanjeo.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtuqlmavjo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtwympatix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtnjmtulcl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gttwttaoov.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtdryfelnk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gteqyxxnst.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtuitdfrut.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtfvqrpghx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gtqwkjrpeg.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtdwqszdxr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtrqtmjslp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtlgskwexl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtctfbludx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtjpinupnz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtyzihiprq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtmtbfrekj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtozifcxlg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtabfinmrq.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtsmhhouhw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtlasdygxc.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtdpxudrsf.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtrgpmyvcy.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtsqdzzmhy.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gtzqyatetz.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtkxenjbul.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtmycyibna.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gtyhfhxmfn.html


<!-- 参考信息 -->