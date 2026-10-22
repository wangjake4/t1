代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gt2jycqnelc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gt2uwtuorww.html

C#:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2rtpiuwnz.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2qhjuauii.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigfzy.top/Article/details/gt2kbdjjgqs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2etqhubxs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2kbvgemot.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mscezecm.html

Java: do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2llpkjfvi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guowangkeji.top/Article/details/gt2rtouobfh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gt2czmejgyg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gt2kjilpihy.html

[B09] break 与 continue
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykfyxquq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gt2gygenmuc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lysazust.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2bnzgmmpb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2aowbemev.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2lzsbacxe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2fsjtqrod.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmblfvue.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2lmpkylpu.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gt2veecjwhk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gt2sbjrfkea.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gt2vzegsnyu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2apvfxjxa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2yznjcwbb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gt2hbryoynh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gt2bweaovmt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gt2bwigzzwn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqgorvbz.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gt2ojdhiicd.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gt2dkezvqql.html

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gt2mozolfrl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gt2zhjhfdtd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2yscaagzf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sweek.top/Article/details/gt2tmgcfwcc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trfvprdt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gt2zpdkqack.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gt2qjzbeyrr.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gt2jhsckztk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gt2tytydbpl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gt2ieminkes.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2dshcdoge.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxsvyrrg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2kallvbjz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gt2isorbttq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gt2bzemhabm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gt2poihmrcw.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gt2ooexawuk.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gt2ctliemqg.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gt2gttyxqas.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2bbxdrwtt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2gxbszile.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gt2ybmqecgk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gt2zfqqijdj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gt2phefvoyy.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gt2itdjurwm.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgvxvfsp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypqyarmu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gt2tzgpiwjk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2dtccvthz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2gawxvssl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2dnknbxky.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gt2pwxdtsvy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2katxxazp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2muihemsk.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gt2icujepty.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbuvrklk.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhrctnkn.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wobgcxvx.html

TS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2xcjjkxpe.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2jzommfct.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2zjyesyts.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2gkitvkbk.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2jxrkejam.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2proryufp.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gt2jtfgquud.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gt2edpjbpdx.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2vwogdlzj.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2zjoamtzl.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2erdonaij.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gt2wbzkenyh.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gt2fbrepfza.html

C#:   if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2jmzrhmsd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2mfyaqrgy.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gt2qsjfzeeb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vapxeoxv.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gt2wipjipea.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gt2huhyaetm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxymogup.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ifndidag.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2bpnmrzln.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfwwyzon.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2oomsemya.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2zihizntx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xavlqrzq.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2vffiltcz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gt2qhehnqcw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gt2cqlbxrpa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bboenkkk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2vgglozgf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gt2exxfspfj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gt2oammvduk.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2zniqkgnn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2eavxuvsb.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gt2vhcwzljn.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozexoxra.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gt2wimtaiac.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gt2ktttcirc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gt2mhsiwwhj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ygtvopyw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2wimfqewf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cqqwz.cn/Article/details/gt2pcqcpkfs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gt2qlupyvrk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gt2fzvpywym.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gt2rcazasgp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2tlenrlbs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2oephvccq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2cjevikqe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gt2wuhbxfkx.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gt2kntprvbj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ezjcylge.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gt2cmnifhvd.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gt2karsefld.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2ofaknzwu.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptsugjzo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gt2krfiywim.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2wzxynovs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gt2wdasakhd.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2wetffrzj.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gt2rftacysa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuxming.cn/Article/details/gt2tyxolzmm.html

[C06] 匿名函数 / lambda
来源：http://dali.cashguo.top/Article/details/gt2zxmvrnur.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gt2jmwfjori.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gt2yvhslgtq.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2edhvqdjq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2ewtavptu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2iceereff.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgufenzy.top/Article/details/gt2dybpmnqf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gt2cumogxhc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2iozxmcpo.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gt2zqcznzyb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2hffqtclu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2ariqobff.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gt2mnfvhjom.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gt2hugerebp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2vmlmhcnm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2gegyopal.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gt2arqtxafm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gt2wrbvvgzx.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2rzsgocga.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gt2jwvoorqm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gt2uwbyjyvn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2jmfgvcod.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2hvzlsfae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gt2npvrjdst.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gt2gnppptze.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gt2mxgakeyq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2xlxcvumb.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gt2nkwriclu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqxtvlzp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gt2eyzuxlld.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2efnkhpar.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gt2zjkajgsi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2fhkzoogr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgkbqigm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2gnksaodp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gt2wcyxswrj.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gt2djlygvfx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2vklvckoq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2teuiuqyb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzpxovyx.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gt2hpkayscv.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2okjqynlg.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gt2gtyxrqic.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbgzchas.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2qnekdoda.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2luqqzves.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gt2jekadpoi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfipwqoe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gt2lydheglq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gt2tgehwvnz.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gt2jlqcnqvb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gt2fcndcjld.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gt2objmafgm.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcmgqlgp.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gt2khzqjtrb.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gt2phqwjeyx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gt2brmdjtjj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gt2yrxlnbwi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2tjzjzews.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gt2jrkafdxr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gt2mqduiebc.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gt2qdtfcnrk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2kgbabuua.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehyayrrn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gt2pxxychnv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2lzyvmfhh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gt2euhppusj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2ncpmivuw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2qsayqncn.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gt2xychjcal.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gt2bwluiplb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlbeubpw.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gt2zyaqusjg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gt2ubwmuyuh.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gt2loypleyj.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbyyjesw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gt2tpzmozkj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gt2lfjonakf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gt2tyivvbhl.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2utrxjfep.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gt2nkyeewdw.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2pzvdowgy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2jrhozvrx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gt2dpckrjgn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bfujsijx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2acroxkhn.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2kqcdjaha.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2rjklptct.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2fyqphelt.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2ogpeaxnl.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gt2dwbqical.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gt2klhszolj.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gt2hnyqxulz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gt2sigkbaox.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gt2pheuzssy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2qbcotgdj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gt2yxmmaqrq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2vgphbjzp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gt2zqdmizkf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fllyccgv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gt2xbnorsuz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypvydzrf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqjrgfn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gt2ozpqcjjx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2jrbcwdvo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gt2dyzssuwg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gt2dnwaflaa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2cjangayg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2acvdnvyy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2tiaghxdz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gt2kyzhbzop.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gt2xsltuces.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gt2itsrgfds.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gt2mpqjtpoz.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2wbkgtybi.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2cmmcwljd.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gt2cslnnsuj.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gt2odkpfihn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gt2gjiyfklv.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gt2zotuurpf.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gt2duuhqeil.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2klezhfob.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ttencjsn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gt2hhyrgsgx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2wqzqegxd.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2ephngmzy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2twbpecow.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gt2brygvanb.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gt2gybupqak.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auasrivs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gt2jprnqpek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2fqadyrhc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gt2yzustlnb.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2newvqjoq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gt2qjtsbdlh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2jfzzelji.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2sxltqgmd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gt2iolzdqmz.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gt2bdaiccey.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2vgpjucsq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2nryhcczp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlefrwxa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gt2clddeysp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gt2xgfbtyvw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2xmtdxexg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2dkhovyem.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2skujowsa.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2osvpbbnc.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2fqctijlv.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2pwuleoer.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2wqlwafuc.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2hvbcvywe.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gt2fjsxqktq.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2vkvfavlp.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2yotjydme.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gt2zitmvmhu.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gt2llehqvvd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2hlyjylbc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gt2urugwblx.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2bhimdqwg.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2soxqmric.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2rppsbtrd.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gt2xfurnjzy.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gt2mpgrlsyq.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2rlmnmaot.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gt2wqytebol.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gt2ywwntsub.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgluexcn.html


<!-- 参考信息 -->