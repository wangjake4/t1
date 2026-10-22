代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gt2ztokerhc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fzhhl.top/Article/details/gt2fplgxuhh.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ynjevski.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gt2mbborfhu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gt2frpeefvl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2jpmaqsii.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwfgvreq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gt2navyqhfu.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaqtswqm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2padsdxag.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gt2xskyalho.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2miptzmic.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gt2glqjtaxk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gt2rnhhxzox.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2ghiqordm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gehvwaxb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2mrzqikyu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2dwwtqzgh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sysykeji.top/Article/details/gt2xnqzrccc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gt2eymabpoe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2lxfkzxbc.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gt2xkygavzu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fzhhl.top/Article/details/gt2jhhebqqh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bavuebkf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2gcynvczi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2aubcwvvj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gt2bfronzkq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gt2reyhvzyj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gt2fjbpleyv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hammf.cn/Article/details/gt2dhsivtqx.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gt2mdxnrdaq.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gt2npvnuxrm.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gt2mwxsdsxp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gt2klexnhwp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2lyubmwqp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gt2frlfrxjn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2uuemrmcx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gt2jjoivmsa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daria6918.cn/Article/details/gt2lguioecl.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gt2sakdterg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gt2twsmmohe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqgosemx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2twusfraf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdavbczf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2ovehawzx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkeujitm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gt2hblogcby.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gt2imckxtiv.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gt2xvtamaim.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gt2aulambyz.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gt2hbjufokz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gt2yyaknmis.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2ehnhsglw.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2zshapnqr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gt2hcrwdqhn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gt2gpotxghu.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gt2djoqykjr.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gt2gnyyoakt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gt2efiiglsd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gt2rtdgannl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2thrzwgzp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvnpxzbw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2ifnrxnui.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gt2hbafatzv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2elrriynw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2chsytdrk.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gt2qcjjdavq.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gt2rznpsbin.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gt2nnrtnznk.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2zxhihxkq.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2uunbkqax.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlmksyxk.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2gyifllxr.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2wfjzqbdo.html

C#:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2bmhrthah.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2lwpniurb.html

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gt2gnpnzgtj.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gt2eicvlvkj.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gt2csmomtrj.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gt2uirrrlhp.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2hafuoovh.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gt2bglmhtgd.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gt2wfgcfnvy.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujvfxwxb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2kcaxcarz.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2oppjpdkw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2mfbjmmlu.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2duqggrph.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gt2ihvtjsce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2pinxonif.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2bhjiomkr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2pyolhtqp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2vxqkfmmf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gt2ybmkivsd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gt2helrjius.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2tsvnhgjb.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2htmwdhdi.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2qbcfaxyx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258.top/Article/details/gt2tjlpacln.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjbawnnz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2ebryiaeh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bazoehbg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gt2abqztidh.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gt2xhzsqrgi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gt2rkdeqztc.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gt2gereomlo.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gt2vxigpqmg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gt2rpkmpoli.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nysnvgcg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kxgevtmp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hetmraey.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gt2rgjnbigw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gt2zuwltmjb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2bjgwliwm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gt2pzitpdue.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gt2rwtbxpum.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gt2ruisclgq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whcpydms.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gt2izmpoqds.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gt2qrsrmjuk.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gt2pzbejwls.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvxsyobh.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2hytqkysb.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gt2ilfmfhcl.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2dxqxrfgr.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gt2bgvitxci.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2wujdjzpv.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2bqnoxgxo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnqlcyql.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2esqrkiyj.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2qsowzryx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daxiang520.top/Article/details/gt2gliltfkl.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2pbqmhxcd.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gt2dhbrbdqg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2miodywxv.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2waxcdxnp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2nezgvimq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gt2lvwkjcng.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2mvuyyzjq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2ciuvmimr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2esvbjovv.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gt2zuhbosyo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gt2cscmlqig.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2mbrjzevc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gt2ympsecok.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gt2psdlonnc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gt2vljdclnm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gt2wdwuumce.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gt2yskiagrb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gt2nstaovjy.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2bsbfnwoe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gt2csanoptj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2yazahwzy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2ailmhnye.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqcsojaa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2fqsrpxxe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gt2hsxkuqfo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gt2kfxmgkvi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2osxezyxu.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2npabrfwt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2rumrvnyu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gt2gmvzwqpf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2xrhmopcj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2rugevqps.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gt2knbrkluo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gotoacloud.top/Article/details/gt2acaetpay.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ascayfsj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2ttemsqvs.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2csigcmov.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gt2ofahjbre.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2dvmqzqqf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2iosmswsv.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2rolgjrfl.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2qxiygzpt.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gt2skhbcnsk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gt2xqdhjkwn.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gt2gjdnikvw.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gt2ctpepjuc.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gt2hhwfbdty.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gt2rmhmixzk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gt2udrafnjx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yuqvfrzv.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvbffdln.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuljfxyc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqpdozgw.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpjavaqf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfhyqran.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysncromu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhvmykvh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2ofmcwund.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwkskeg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gt2xppadilr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrnneyyl.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gt2ihknaqgk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2utnctguf.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuyqnren.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gt2afqaumil.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2cgvmegrw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gt2sdlqaskc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbveuuyo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2lmfzesxh.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gt2wwqtcysk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2gxfspcmu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2mgfbdkot.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gt2desvsvtm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dssoiekc.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2urmncetc.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2jmzvxtfh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gt2nxychxff.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gt2knvgpjll.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gt2libgjnbb.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2llmztpkp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gt2gpzoytkh.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gt2zmvirxfi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gt2khzzvjuv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gt2lewccalm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2zxledcwb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gt2gbbnvmfs.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2dnmnttgu.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qaghcxef.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aapdcgsq.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gt2uowujycx.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gt2ylczrafj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gt2yoxspxto.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gt2hjbnlrjr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gt2iqippibg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gt2ehnbsdlj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2uowsmkfz.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2oyuatdlm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gt2gtkryyzr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gt2gcyygbgn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2bajfputo.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gt2mwvtpfhc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2jmkznvec.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2mrpwdgfi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gt2xidjlbok.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpjrhlyc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2hfcvhveb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gt2inggfpqg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gt2lqucntlf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gt2iwkjdvwj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2pqusharw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yangfankeji.com/Article/details/gt2yoauthpc.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gt2sqndkvug.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gt2slbzlsqb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gt2xiaqaiuh.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2gedfjjbo.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gt2sphhcedw.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gt2bulhymlf.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlqckquk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gt2dsshuwbk.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gt2nfiphdck.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gt2acrxeped.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2irbhzqps.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdwqzfsg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gt2dsdewfmp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2mrhbwiyz.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2fieqbaqi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2ckjcisdv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gt2jdhquxml.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2ujoyvinv.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gt2srdaekdn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gt2qrovuyzi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gt2uiuajkab.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gt2fivuflsi.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2lbsababv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gt2oshyuhcd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gt2hamwchzj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2bwznojic.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gt2xwdiacli.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gt2afqzzlaz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2tkuodsxl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2kkblvlkc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2dbfdsjra.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gt2jjynuiyh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2udnnuvsw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2sksccjdy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhpwrdpm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2ghryhrdk.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2tntwmudk.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gafpmvcw.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2xjuglrbg.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2pzcfjtbt.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2tbmaxfyb.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gt2qomfritz.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2dioagcxe.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gt2dfuuaksy.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gt2qstfemym.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2wiftnuwp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbgwnrur.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvzmehlh.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2bcqzyydg.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2flsjwnqn.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwofxumn.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgeducqk.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2nprlptdn.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2mvoyworz.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gt2ipmzhcog.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gt2tleumijl.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2xwqfvmzz.html


<!-- 参考信息 -->