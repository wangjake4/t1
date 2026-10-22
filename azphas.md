代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.fengsongda.top/Article/details/gt2xswpigik.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2arngamnb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2wowpvgyn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2cacndvxx.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2rfynbwoj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gt2pofzbtvp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gt2xsfjhqbo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2jhsrhgfz.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gt2ugpnvrxx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aibaodan.cn/Article/details/gt2siheoilx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bybqeije.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2pbbvyfjx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2gpivtpga.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2flgmnthe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gt2jutecylr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gt2ywtwhvlx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2rpxelnkz.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gt2yhchipkc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gt2mrbkfgmp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvmhdutb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gt2lajuhvwb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2cvqpfpjw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.quarkkingdee.top/Article/details/gt2reoovdfv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gt2itkdqdtb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2pknzyanx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2tdsydjli.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gt2elhwohlm.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzyldkhr.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqvbwojm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gt2ykmpocgq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2ymyxufeq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2eaegulei.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gt2frzlsriz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gt2eddlthde.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2imocjyuf.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gt2fqamnzdn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gt2bfkgdeiq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gt2nppmasrr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2nnkbtvnn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gt2irnmhcil.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2kezgehqo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gt2mjfzxkqi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gt2rfcytvzv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gt2ivcbkyly.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gt2fqscmowl.html

Py:   isinstance(x, (int, float))
来源：http://dali.gzhubu.top/Article/details/gt2flwjyoij.html

PHP:  is_numeric($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzypubox.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gt2aezcufep.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gt2uyrznfpo.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gt2utjhsdvl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gt2qjxpppif.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2wmlkbuiv.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gt2ludxgguq.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gt2kiezorfw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gt2nnxmeuxy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gt2veljqsds.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2xquqlnvj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdjaixij.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2uyxdlggu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gt2xqlnupaa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gt2ayrmxkdf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2ulowmoef.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gt2vtsokmfe.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gt2ewublpfv.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gt2jacdrvnt.html

JS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2buezwmgr.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2ttyqmrad.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2onrszvac.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2yyzrjerz.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2npdzbtph.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2tsidzwxm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gt2vaaqtviu.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gt2nkwfvaus.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gt2zlbnzxkx.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffimhobh.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gt2iwdstcnx.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qryidhwf.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gt2ihmgkuty.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gt2mdzuqlvk.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2gyggelju.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gvsikbse.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2tuzjkqva.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zgejngtf.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2erqtpurg.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2itjefotd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2nfijivml.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxjfqqe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eezfdpby.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2lkirnnnh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtntjkxa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gt2zxdkwjvr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2suncddce.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykjzwuug.html

Py:   def greet(name="World"): return name
来源：http://dali.316326.xyz/Article/details/gt2xxtuekvy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gt2tvfeyiaz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2wjgfwbal.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2jlzbmwob.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gt2xcoevcyk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gt2yltpjfms.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gt2dmwqpecv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gt2jofjjpzo.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gt2bwufflmu.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2zobobosy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gt2dbouquwk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gt2ijkppfdi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2moudvevm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gt2ygiwcojw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gt2zextewzj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gt2jtbusqmw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2jsfzhhje.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gt2xrbddnhn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2jgdhycvs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.mhx1999.top/Article/details/gt2djzztztf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2bdmqcfff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gt2xaupizce.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gt2npmvewsh.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2xmxpffza.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2mmsvomej.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2bjnwbwtj.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2bihzlqtd.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2habukdil.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gt2bnafwtft.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2pulkvmcg.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gt2uhmefejo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gt2xbhljxkl.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2flnouwjy.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2rqsnavmi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gt2xafzpuvt.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2kuudstwa.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jybhrfyx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gt2tegmwslk.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfiqakqu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gt2rfrqaifv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fepyrajw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gt2juebawct.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gt2cyjedoil.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2mpibmutv.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gt2mamidrth.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaerbxo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2wruxjrll.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gt2bmpnqosq.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gt2pmmexuku.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gt2lfblmmph.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gt2erzmhjhn.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gt2qkptjxje.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpokyltw.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gt2vefiypur.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpgirkjx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oknfurca.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2anpkmisk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijedwcgt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gt2hyskmyza.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqkdyrd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gt2jpfdworp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2ioyruyzx.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gt2mctxtdsr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2itvjvnlv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gt2icztkkjn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gt2efrfrwnn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gt2mdczjwzl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2lbnqogum.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gt2fmfusirb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gt2yiwfwxmp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gt2jtlucokh.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2essxcxyb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnaxjbrg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gt2iqzkbxoy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2vfvhklwb.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2nkfwifaw.html

Java: 方法内为块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oksckgky.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkjswrkf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yueranfly.top/Article/details/gt2znqsklna.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gt2irozbucn.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvnrupqe.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gt2txvviume.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gt2wgolqyuq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anlrhjzo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gt2puxzyalv.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gt2kbemiyib.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gt2ejvmxybz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gt2mrlmwfvr.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gt2vrncenvm.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gt2mkvegetc.html

Py:   (lambda: print("run"))()
来源：http://dali.9152youxi.cn/Article/details/gt2wpweuwpn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gt2aeyqxtwy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2dxeqgogr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gt2vreufzsx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gt2gntokodi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gt2ikxxyrwz.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gt2puffybzv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2qmsvhoxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.aizwys.cn/Article/details/gt2sifkeukp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gt2ryzznomn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2skcbswyq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2miojieod.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieeenwtq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2lprxphhf.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gt2llolmvky.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2qabrzgur.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gt2debqokbr.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ayupslgn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gt2lgjyqspv.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2kilxeeqk.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2ywtoylli.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gt2dmtisfqw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gt2xgsjwbho.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2jjjtdxji.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2unorjaqw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2qycohdzi.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gt2nbqljpgd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gt2memzmjkr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gt2ukhfqzbo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmsehlgc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gt2ozwzihcm.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2ixhjvvnl.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2xuqhwjkm.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gt2clwregpd.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gt2wyxevjrd.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gt2qoqpanck.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gt2onjsysby.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gt2cqollfsl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gt2larixhnt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gt2grhcncsm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gt2hhbkqiry.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gt2cowcyqrz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2pdmfaiol.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dzicoqrq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dohxttdw.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2haptngmp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qlkhsnhi.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gt2noqnmqhp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gt2blgkqjue.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2lwjudkla.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2gkcqftng.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2imwhtvqe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gt2bhltulmu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkitmkwi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2wukakgbt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gt2otkaikea.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gt2dqzxpgrd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2uwoarfai.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gt2skwluykz.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gt2slejndck.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gt2vaiaxlax.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2xvneqrek.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2vpiydwxr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gt2roxtosbd.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2wmdjqwav.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gt2plmsjwon.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2sekuarxm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gt2pquelzbl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cktqddeo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2penjzaku.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2rhbkjzlx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gt2kyulxgdq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gt2xqcijqwz.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2oejqfykv.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2jnnmnynt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gt2kloppkfl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gt2wrltgomp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gt2zteodflo.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gt2ydjmhjlq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gt2cyktatrp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fengsongda.top/Article/details/gt2rsuoanxc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gt2ktmnibzi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gt2ufntiowe.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gt2ntptvqhy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2bfdywlqs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2xeoeuqth.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2iufuopvx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gt2wvtzdhkv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gt2zzpyscei.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2takjvdfo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2udwnnxvm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2wpkscgpn.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gt2bqobjdhn.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2sstuwynq.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2gxyjwqdd.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylpywlaj.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2qhzxicqz.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gt2reaobsob.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwpwbtjw.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozigcstl.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kltrbujj.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gt2lxguwlub.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gt2ebipztot.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2afrcgjcm.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jddcpzah.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2vxwowcnf.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2jnruthjm.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gt2slaywppl.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2xefiyjxq.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2ibclnqjb.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gt2oxjnoynj.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gt2sdkhmtnn.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gt2okdpvbdt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2kdpgxtoo.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyjfkdyt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2wfrgjlme.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmimufuf.html


<!-- 参考信息 -->