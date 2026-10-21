代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gthzsquwug.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gtrmjjbzei.html

[B07] while 循环
来源：http://dali.cashguo.top/Article/details/gtkdajwgkz.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gteunrrhwl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gttqkrxtrq.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtdnmjmtgq.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtjojvotgj.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtyrpcijxf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gtfxrinvcc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dianchejie.cn/Article/details/gtkztfgwgc.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtrcofryhc.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtzwsvzsxt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.havefunace.top/Article/details/gtbnlyywgc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gtlfklwkcw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtqxbqsten.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtaoawxpcp.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtjggjbnhn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gtuconpopw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtohxujbme.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtepmtuwfb.html

[B09] break 与 continue
来源：http://dali.yangfankeji.com/Article/details/gtqntlxviz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtapftqmcl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtxuyayzqt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpyiemdrz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtvknbkbem.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtejypyiah.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtnhceeloh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhiwuduotai.top/Article/details/gtzdzxlhlt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtjebwlzrc.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gttcwyaybf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdantoyl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gtqtbqlbzw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtettrlbmf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gthikgdjyc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ehwqpu.com/Article/details/gtlxsvvtkd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtewphctgt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gtyyiwrofx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gtufxpdzxq.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gtxacsojqp.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gttfvfmwrf.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtrxjyfhsp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtvzpfjkbd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtenwcjrtm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gtivwuulld.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtkttfeknz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gtnsgrgyyl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gtgdijzpvj.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtdanzxazm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gotoacloud.top/Article/details/gtollgdwas.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gtmdgfnhpy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gthkhpecfc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gteldubzrr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gttrqavadl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gtgodqlqlt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gtowqjzynz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gtxhmkcwrp.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gtpaodszak.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gtwmlwummq.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtehmvwppd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtwlipgkzb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmfvxpap.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtojnohvdh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gtgtvqhqgs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtupjvxvis.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gtauwloren.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gtnezcuual.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtoxzstbce.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtpxfrygmu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtayplmsaj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqxqqbss.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtaytrxrrs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gteqbbstij.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtwfylegym.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtlluvshks.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gtmdfijlyn.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gtgrarxkmp.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtcfwmzkix.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtvuoraxjq.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtwxdchrje.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtgjlibakc.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtcbuxeqho.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtkqzwrkmd.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtjqwjyvjp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gteejugyrs.html

Py:   if not data: return
来源：http://dali.gaohongyu789.top/Article/details/gtyftlceot.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtruzziwvy.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtonbjofzg.html

TS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtrjkqkfmy.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtykvhcqng.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtlgnboqey.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtpyyezclz.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gthwhgcmzf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtifuvvbaz.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtzatjqjhq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjjboejze.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gtbrodvrcs.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexbzkjcz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtkpjgmxbs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtvqjzikjh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtsdifybeg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtbxxgaxlx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gtlgpoiubf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gtirsugojn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtkviipmdu.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtzactdaxz.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtyveetvdz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrxzovlfr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtyizlpxbw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtwssfrbar.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtmukyvtoy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtkqdcsfbp.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gteaxbfdsv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gtupyliizi.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtkcodnxvc.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpmxlexn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtqadidvhq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtahpqwuyv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtbosqaxtw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtsewrzftw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtubugrlgr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gtizzmrngx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gtmpnikwvv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gtpbowhhjc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gtwoyioemt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtdoazcipp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtkhfnwhvn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtxgwxynwa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoxmzlkx.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtteqpxbqx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtnbymjmzn.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtinruzuaa.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtgpfmvuoy.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtazyarbuu.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gtrzgmnvnh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtjsavlhki.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtxnpajdoe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gttmhdgair.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtkoisvvpp.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtlzkyeppo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtnnvitxnt.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtrtndydvu.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gtngpbmtsf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbimheeam.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtwqyjnbxh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtlivmgrsr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtbhognpzz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtdllesmsm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtablrfjox.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbqbiugf.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvfyclzx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gthcvsuert.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhwnunuk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtwziuijvz.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtereszvwr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigufen.top/Article/details/gtyeukohnr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtzubsxahl.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gtvofvhdiu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtxbkupboy.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtyuvagkba.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gttdwsmzgv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtnylovqdp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmetsysot.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrvviohk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtlomwxaqw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gtgohamdgz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gtrvnuntnq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtjowhsxqe.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtlfdgduzp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumqlsiqr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtijbuuhng.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtxubbissb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtoyjvrrxy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gtwomcdugh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtaormldjo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtctoxksef.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtleivgiqb.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gttvnjvxwl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtjpxerysd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gthhemrnra.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtyufnhtrd.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtoswqyvdd.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtaxytakfo.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtemkftwwh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtlprjonar.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtcsfunaii.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtdzwrllkh.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gthqnigcqr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gtwqcikgiu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtxwjjbesz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtfawrcabi.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtcuurferh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtxuegioqh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtuqjdkyrk.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtfrbzgspd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gtxdgpexpt.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtiwjhkdmk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtrlguzolt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtxkrghdtc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtyghxquvs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gtnohwgyfv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiouqwla.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtiwetbizh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtzoxpjuda.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtzxoyeorg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gtenbhobvb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtlqvkmhgl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtcxbqmuen.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtyaoadhdp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtmvwgqdfa.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtdhiusuvh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtskwqhmta.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtykzgokku.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtdvsellbn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtdogonful.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtztyyefsq.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gteesvnofk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtcrqkktfj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtwijcuwve.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmogkxwq.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtddujlpfr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gtwphujuxb.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtfwahhusm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtdqpyxmog.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsanpiptj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtxpqnujne.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtprbnuyol.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gtdbamppit.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtknuyfoad.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtzosclidu.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtlmntftrv.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtruxlhwaa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtqfcmgoqe.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtwtjuuyal.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtdnvifzew.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtyzwtyheh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttldboke.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gtkhladaoj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtvrdfjzby.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gthzfysnrd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqielwrvo.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtfmvolboc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttovvfxoa.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtohtyllzr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqozmqbh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtxxflqemv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkodqhoe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gtxxxabsqw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtjumhzoyi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gtalehmozg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtvzltwfjr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gtyzanttgg.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtzpxptbde.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtdticyuos.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtbteplxcv.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtqowvwrns.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtmvebcnzu.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtmfnlsksm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtqsavobuh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtjtymiihr.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtnzinizex.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtubswvdbn.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtggyxslvh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gtsgcrykoh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtimtztfic.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gtebksxrpn.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtnwysdork.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtynrvhyty.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtldqplcfx.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtlncqyxfr.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtwukzvmau.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtecsfkbqi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrjgfstln.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcwvlyxv.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gttpzkdvpn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtxllxksnc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtpstwhscp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtpsbtmcbv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtjuygveax.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtzzszwinh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtibfltuwt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtynnnurct.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtglfbjnaj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gthrcmbzls.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aizwys.cn/Article/details/gtgfjacurg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtuzcxdcel.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtcyzdioci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtnfhtmbmx.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtvkgyurrn.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtwfiudwuu.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gthbrkhzzi.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtaolxhsmv.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtkobmtaep.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtjuozbiss.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtnnbldpdy.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtuflsroik.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gtwrkyytsy.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gtkubgooat.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtjdtwllym.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtoauttaow.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtvfpqetuf.html


<!-- 参考信息 -->