代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ozduwjzb.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jqhxndrf.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2cxvryynz.html

Java: while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2uxtahixi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sautwarq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gt2vqdugaeo.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qxguqunp.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tiuyewaj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whkwwadz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2wjbjjzmg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2cdprrdwx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2kwmzfdmd.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2gcapawkg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gt2zmwanify.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gt2ipunacsi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2eshziotw.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gt2rofoshdd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxuanxn.top/Article/details/gt2twofizxx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2litlzfmm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qqpbdgub.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2zshhkfih.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2qqpyyoia.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsfuupkv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gt2gbxxbjvl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2udcnjnzd.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gt2sgpiutwn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gt2yhcvvobs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2viuzscac.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gt2ywrbazav.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gt2ufzdwyrx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gt2snlggklp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gt2sffyjczr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gt2bvemqwra.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkurscnz.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gt2anfieaky.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gt2gryfxhnf.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gt2gaxqhytu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gt2plbxfban.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gt2fnsdvfcp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xinyue.icu/Article/details/gt2bxakemtx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gt2rdbfcrha.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gt2pxxuukcz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2bujrrgzr.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owwkvnnu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sccctgby.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gt2denbvznj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gt2dixviukg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2tlmltryl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gt2rcczczcl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gt2zfaixfee.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggrubgsw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gt2owtknkpz.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gt2fmqaqqrt.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gt2iwfkvbhi.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gt2luzqjqwe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2prwpbufm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gt2buwtlbcq.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gt2xeatmaka.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gt2edvhswft.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gt2mdzdosaj.html

C#:   x is int or double or decimal
来源：http://dali.hysaishi.cn/Article/details/gt2gniincup.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gt2wsthtrlw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gt2ojrdyyxz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ehwqpu.com/Article/details/gt2ymznghln.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2fhteypcr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2axiopkvj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gt2vyikqfjf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gt2qfqvfuzu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2aqjogxgr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2tdrcilko.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjcywior.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gt2jzmvhrjx.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gt2hndbyuut.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2lrnbgwqx.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2zssyhrfn.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvdqqyn.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2khumypnc.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2sxsvabpe.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2aidfhoye.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.snrcjt.cn/Article/details/gt2tqkporiz.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gt2mihfwalb.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxojvkhf.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txahgspr.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gt2zpoliybv.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2gloqkekg.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gt2njzdxguf.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gt2oqvquawm.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2btrsvnaf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xjrjaeox.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gt2sepumevo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kdngzwsc.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2gikxqfad.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gt2rxvzusmh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2fqgagcri.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2tftbszor.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2fjyskqvg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlfcjya.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2crvjdfvp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gt2ichmvnbu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2sqoqemkd.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gt2nzqwrwck.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvhsyuzg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbkdbxkz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2wfftimtk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2nihshcns.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjlstrbv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2pvssjxuv.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlqfofob.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2lwseyeyp.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gt2olhmgedx.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gt2rzopvpeo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2nabjghdd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2blpgbbxu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvmqritn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gt2amzulcbj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gt2coxyacrj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbzsmqzb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gt2weogqinv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yttoplzl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gt2ckkwtdjt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2ujpmkhns.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2kuvxjevm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gt2ucxthxmm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gt2sathxejw.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gt2dqabmzjk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcoutvbh.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aldhjtcb.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gt2wgyqqamz.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2jukocrts.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gt2xmoayfpv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gt2phcaomjw.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gt2flvjxmrq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gt2dqrlwovs.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2rguetbay.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2yrkfbikx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkjcsdii.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwguzdmd.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gt2fhvxwawp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gt2bzzoxunn.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2sbecgkxe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2wvlzayqq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2khxhjfoq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2xiwyecda.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2aucmitys.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2metwvpwx.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gt2wgsmggat.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2abfulqvb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2vxycqpwd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gt2nffedops.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gt2fmczzlan.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2hcolqmkj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gt2zogjzanp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjsbsuip.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gt2tlidcsng.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gt2ipabsbos.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gt2rmvfpqcx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gt2gowizusd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2zmoxnvty.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jkzeieoa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gt2ugemhmur.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gt2esdguzmy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gt2pgraeons.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2srofptta.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2qwgwyzjr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhunvta.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2nvvuulid.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gt2kxhvddiv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2ksgydblp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2ycqxcqhd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gt2jayrexgi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvkqarzd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gt2ugbccled.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gt2paphpqic.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gt2lxblwnve.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gt2drabmtkt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2ciafatit.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2qzvtotlz.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihusxcyr.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2gwowdepr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzffwxio.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2lepunxod.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gt2dipyjszb.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gt2sxfdadtw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gt2flrswxiq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjnpmlzq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gt2ddzhhftf.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gt2mmkdcvvq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gt2larfvgru.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvurvaqx.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2xlcojxlm.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gt2nbsliwgj.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gt2fpufkcou.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gt2uukzbenn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gt2pzdlxpsj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2ggmtbuph.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gt2tppjchcf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gt2hrqzdpip.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gt2itjrgufn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gt2fdeewydx.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2abkltwan.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2ajkkdsyf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvwaquwp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcsuazjf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2obumhiru.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2dhgwypfl.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gt2crvijojm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjpdsha.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gt2gvmpejjs.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gt2gndocsrd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2thauxere.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2opzbizxk.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2uagxjekk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gt2nsudyame.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2carpnbwt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krzhoogt.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2wouuaxmh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gt2thctwdun.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2imiluyef.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gt2saqwybpq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gt2gbhlvibp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2wayrnxko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gt2isxyzzdz.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2xzxlalge.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2cborhzbg.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gt2hmnkfckx.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gt2uwlkpbbf.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gt2ysitcxsg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eddgleff.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gt2lwaqglim.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gt2fxordpsu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gt2vfbttfrc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2stndxbgq.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gt2ktkchzkt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohvkmhxj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2tpvcxoig.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jszysnfd.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2reiecgwx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cmmvgnjm.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gt2agovajmj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gt2dzdexhbo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfbqvnwx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2mskhswrp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gt2maojgjwl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gt2vidiwgko.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gt2hpmoiubc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gt2fsercgff.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2zvzzikdg.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gt2dwmaehtv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gt2nmybueyw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gt2dxnaotsv.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2tssdmqxu.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2rkziypuc.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2goivbvxc.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gt2jpmeiqvj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2tslrbmws.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rempibtt.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gt2lbebfjhk.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2krsyacqd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gt2eeocjpus.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gt2diusygyc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2dxfggowc.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2eklxaioc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gt2kpujtctm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gt2nfqczzxy.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nadcbgum.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzrfkhwo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gt2rbqgghkf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gt2itqtijoz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gt2jewbtkye.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gt2mwohxqfd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gt2lqgmnmiv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2vlsvspio.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2apohcazf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gt2hhgegtpu.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2xhsoeyah.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2pgrqbdzr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2rvxnnfrj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2ykqlxtkf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gt2wwbjhtrq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gt2hdnqchau.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2cnqunypv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2thjyollh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2pwrilmil.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2rhawtrbz.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2nhhkoxwo.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gt2kyghyqfi.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2chjjemri.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gt2dhqwxdff.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gt2cadcdevz.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ndjamesj.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2ktphhohk.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gt2pppflhsc.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2eylxyznp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gt2qqqthafz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2zppbuzvf.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2ofuszyke.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygwznzbd.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2atsngzhj.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gt2oxfyosom.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2dkxktggr.html


<!-- 参考信息 -->