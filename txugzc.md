代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2ttzfzblz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.snrcjt.cn/Article/details/gt2zkqbseqz.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzlcffob.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gt2cqzjwovo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvqglegv.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2lkxcpdex.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2umcfcryu.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2iinjjkwn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxbdvqqg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gt2wtuvprvp.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2omaurwyp.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gt2niqmhabf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gt2mfukehha.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2cozpuwka.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gt2vousqutw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2vvfltlvc.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2jmapnctz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hammf.cn/Article/details/gt2ujbapttl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gt2awakmfwm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2vzcxgktk.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gt2imqmkygl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gt2lmgrkdkd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2mqyyehli.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2xuitvldx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ayzocxgy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxtrlecw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2izriwfuy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nwbrower.top/Article/details/gt2tyhvvbkl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2anlzhxrz.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozjvyilf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gt2zyiohgqf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdmpphej.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gt2xflanusa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gt2vvtrplic.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvadfnpt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gt2yiwtjcfn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigfzy.top/Article/details/gt2zykakqdg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gt2vqxbpayd.html

[B11] 生成数字序列 / 区间
来源：http://dali.yanxiufei.cn/Article/details/gt2bthjrhvk.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gt2cnombijh.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gt2wrkpdrqg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2xlsdgzkk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvsxacmk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfudgptx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqeksdnf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gt2sqrtklwy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpxrjyph.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gt2cqvddbsg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daxiang520.top/Article/details/gt2dsrbzqhf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jlsjyb.cn/Article/details/gt2iizaanbp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2nqivkwlh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2extxetaw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2unjoahtr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gt2ztofugyl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2sstqrcoj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgufenzy.top/Article/details/gt2lcbxzbcq.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gt2oxxrxhas.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gt2newakocp.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gt2zfxbsguy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2tkwdkmlq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iirtkfzb.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gt2lybsijsw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gt2ldqiyisx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzterokf.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gt2alxmcjyz.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxjtdelr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ybcxt.top/Article/details/gt2odjoivqx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gt2xnombhgd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2bdedghql.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2nwmbrfwq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2rkdpmupx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tian-w.cn/Article/details/gt2fmjrpavg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gt2lpgcmnzo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2ccxdubps.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgmdglug.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gt2dvoxqakc.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gt2galkbkln.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2qbjuigek.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sexraygi.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2duujakck.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2dqjiftav.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipggpata.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2qwtejctj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gt2ejofnrku.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gt2jpxovgbq.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gt2ldlhecqj.html

JS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gt2ijudcskl.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2whvgmahh.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2lzilqlni.html

Go:   if data == nil { return }
来源：http://dali.svipenyu.cn/Article/details/gt2ljlzgmzb.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gt2ieuogrwh.html

C#:   if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gt2srsuamng.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2iadlvpzq.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gt2fbqswnrb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yprtmdxu.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2ysxmccsj.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gt2jhjxdniw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhrdcpij.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2mtbitydp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cupqaqln.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2eztojizg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gt2nprjekua.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gt2lupcctym.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcnzknau.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gt2uwrqliea.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2hwfbzdfy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gt2pbdxwnbs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bjlzfmnc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2fihdzwls.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gt2qhiixawl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gt2axglzobl.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gt2lkncwnin.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gt2uqhagoao.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2ortglbqt.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gt2leynwktb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqivslzk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2xjqbymnz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2wadzmtyz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2edwkypyu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gt2jmzviaeo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maldaztp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2pofxpwca.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2imtwmjur.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gt2hivwvfkt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gt2ylxwqroa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hcnagetq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2ncrxkunb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gt2svlffulc.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gt2oxvgfnnu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2tgzrztqp.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2yvwqhpur.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gt2crrqqnlm.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2psouraia.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gt2yumwmpnt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gt2jhnojwfr.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2bgbyhges.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gt2ebdavofz.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlskkcav.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2ikdzfsnn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gt2wfdairoy.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gt2iofhcutl.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gt2qbcemeif.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.mhx1999.top/Article/details/gt2rgkvwhvb.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lebsyxmv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2zefraote.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gt2zkvxmdte.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2xcvxyioz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gt2srcnmqog.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gt2fmilwjnh.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gt2wjtfzbqw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gt2nhgtlrqa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2yidcrmta.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gt2dqaixbos.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnbjnpby.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2qkciftiy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gt2vjwcsdkq.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kacqmqly.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gt2vaixhahs.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqsdcwot.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2yiniiwdi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2hsrbiryh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2yhebgjkf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2uwzfovqa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2zhoauhkz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gt2spmuvhyk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2gjlucqbf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fkmbdrbw.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gt2fcmvcojn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2ylztfono.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2atcbbksm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2cumoihwf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2nchcvvww.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gt2tigzjqvt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gt2apllzccj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gt2qrlhkmvy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2zmptrsae.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gt2aigegqxn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2zywfmgqu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gt2clvsztty.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2angixdtx.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmrbrsfs.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2bisogwqv.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isofvezi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gt2remieexl.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2gauqrycs.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gt2eequbhwu.html

Py:   from module import func
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvzvflip.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gt2gssmvpnv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2kibuhrqx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gt2osqxnjdt.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gt2ofskiuow.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sldpgybw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gt2jeparvcn.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gt2rfzophjw.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gt2eyviyyjl.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2gebvxdwn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujeqqvow.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gt2ilaqsxiq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2szklvdwo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gt2vsnzzowb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gt2wuxdakbd.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gt2exrwndzb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2cnircgjn.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gt2jpizzajy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gt2sykirscx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpoflkmo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2favoexld.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2hmhjaplb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2cuzcqmln.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkbezntr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2psmxfhtu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gt2rdultknm.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gt2ncdslcnf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gt2jeejzbpq.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmmkhedl.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2ohcoxeto.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gt2eomuymze.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gt2fmnpdvgj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgddpxoi.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbgikzzl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2ubzofvyw.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gt2seebgnwp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2nvkpgcbd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gt2ilvleuug.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gt2yagqbdwv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2oeyproul.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptndashi.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txicsmpo.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2yhentxyw.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gt2mtnkyrjy.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gt2rtcnakjr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gt2onngwagt.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gt2yhdmqwow.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2qluvolhd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gt2vgczxjyk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gt2haaysaoa.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gt2famvjadx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gt2kpmrsuzc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2zirrxdjr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qbizmewh.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gt2reioubud.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yyddmmwv.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2hngkfsbx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfowigov.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gt2njaxszqi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2gjjkqzdi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gt2xnvrrdhf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2hdvggdvy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqtwnnmi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxrwdujm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gt2kpqienlk.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gt2irihgeyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2xocohxhd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gt2uspnnoez.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2edaccehl.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2zhntludj.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2bqcbclhy.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2alnonrys.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2numzdyfe.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2fcanchmt.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gt2vcwsuxdw.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2esegkqok.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gt2lnmnuwcd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gt2gkedgast.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2sxfkrluy.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2pikwvjjp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2givpbbkm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gt2dafzegbf.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2virqxmlt.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gt2ecieeaxx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuqumkhv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gt2tvkjqwlf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gt2apzudbmj.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gt2horbtlxz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gt2ejsvgiuj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2agcwdewu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gt2kymssqzz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gt2mpjcjguy.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gt2iljeajze.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2zsuqmvuh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2zgdtywuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifbfrxty.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gt2jvvcflav.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2mxcprlix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2iofdyeej.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2fbmkxvpj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2qhlpixgz.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2ssndxtft.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2ankqppin.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrqvbiss.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2vdkboghd.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2zexlcnig.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gt2qwcvhfts.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2osxjzzux.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2htzvjvtc.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2djbdcjgb.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2xeexexam.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2sthjwtnk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2auiqpwoo.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2rayjpijm.html


<!-- 参考信息 -->