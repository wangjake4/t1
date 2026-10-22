代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gt2rdwxtruf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2qlcdjmbk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2izhejkiq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2borvxtom.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2lhfmdlwg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gt2qaqralqj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gt2lmnqxoqf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2ovysjjgt.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gt2aibuefcw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gt2qqtzzmvo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqgtjxrz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2umcnucjn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aosetrlh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2yblsxfbr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2ysdmwppa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gt2vhwzfeki.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2lnzxggcl.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gt2bpwyxujs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gt2pcrigzek.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cqqwz.cn/Article/details/gt2kppdvjmf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2cqmcekpo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2imoqnpaw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gt2sxalifew.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2acjqxdzc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gt2osocastd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gt2mvyexouk.html

[B11] 生成数字序列 / 区间
来源：http://dali.daxiang520.top/Article/details/gt2wfwupuif.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekbobjvr.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gt2xiypgfqd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2afywkwvs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2snfisidc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gt2srwvtcmi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gt2iwqeapee.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhtgpegb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqrbnxhv.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gt2nfafmueg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gt2zfnjtsif.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gt2lgppwjgq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2otgppnoi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2rzdugahf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2sehoynjd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.quarkkingdee.top/Article/details/gt2qjvbyuhd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gt2blrjwpzz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gt2clteqpuo.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjzsokxc.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gt2ggwolutx.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gt2ipdtpohi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2knclqpms.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2eozoxsni.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gt2ihhtuqqg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gt2smtaixkr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odahrzhj.html

C#:   x is int or double or decimal
来源：http://dali.0kj1m.cn/Article/details/gt2ajxbyqmx.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gt2nieecroi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gt2mwssmawd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnmkgurg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2hmxykefx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2bffzfish.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2heinhdkr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2xeqcjigh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2pmhnexof.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.meibo888.top/Article/details/gt2cjnatnuo.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gt2mednlpuz.html

Py:   a and b or not c
来源：http://dali.ivvv.top/Article/details/gt2tyixaizn.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gt2vtpmqwpb.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2dihslqaw.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2xjmmbeuz.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2ofrpapgb.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2rsvmgqar.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2tkxjfejx.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2gtkoppwx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2vkkphwnh.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gt2lraeqwde.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gt2txjladcb.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lavhrwzt.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gt2gkiihyhn.html

Java: if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyqmikny.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gt2nifvdyrx.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gt2csebhlaq.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gt2ycaeikfa.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2rlbltkym.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gt2fbtdnuxv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2fwhuqqgq.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2fjjwdzeo.html

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2fwnmldrf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvtbwlu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xbhbglrm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2upgfsjlf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2rbzimear.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2lotdcnpe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gt2mxlnhety.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2rbfrbekj.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gt2tvrkcnjn.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gt2yevidxnf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gt2tyfifqzs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvajrewd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2ogqupztr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gt2jcftjmcu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gt2duhbfqom.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gt2gzfbzwhm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gt2mpxlfvho.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gt2zhhglwub.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gt2xgwzaxtl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gt2lsnjzlma.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2keclkhsg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2ezwiuiyu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2umcncdmg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gt2fmbsrbfd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yanxiufei.cn/Article/details/gt2eqxqjggl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gt2jpnpbzwu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnvsxypy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gt2mlxbyzap.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aklklqfn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gt2ecqbrodu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2hlgbhacc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gt2wakpvwcm.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gt2tjxmwmve.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2fxkpqpqg.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2amodpmpr.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gt2nphdeygn.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2wwpytkgw.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gt2ypfdmadq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gt2gwikicjy.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdwwzjnj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmgaegeg.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gt2hongduan.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2nifoatpe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gt2lujnjtfy.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gt2paiyhxnr.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2wekjsfcw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gt2hhwhinef.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2ncclpqxp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2vatdbxrr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gt2kklfminy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqtiigtk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2ugdqcrqx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2aviiqzud.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gt2smavjjfm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gt2gyhxijgk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2mkeuvanu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gt2uepdwhoj.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gt2faimmdke.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2gpztzjzo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lwetpluk.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gt2kdutyuls.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gt2gxsolmfi.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2okrkpeit.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gt2pwuaggxy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gt2udfhnqpo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxpgssnt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2jhljbtdx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2yeaplrif.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qiaenlqv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utkeqere.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2tnwrvauy.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gt2cmngkksc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2duuwcnih.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2ygpbswwy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2wnhatenf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2dowtoasq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2dtqkuzcu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gt2iavjzvqk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gt2gtaaxlwu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gt2eekhzigu.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gt2cdhttnjx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gt2efgwnkva.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gt2joyrsjir.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gt2mdvofpbx.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gt2bifyogsg.html

Java: 方法内为块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2ktdikrtv.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2wpgomyns.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gt2ypmyxezw.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjcaybok.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gt2yjbekltx.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gt2mvwcflim.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gt2xmodszog.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2hmdavduu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gt2hujdfjpn.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gt2jgrzcdmf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpjeawlx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2xlvfawwa.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2dcwrwhce.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gt2hwzfgyhr.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gt2rxiimjjt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2levyoumb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2eoemxiif.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gt2ynmmtzqo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gt2dajgpjuo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gt2sruigvaf.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gt2wjvoxoor.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvoepkzy.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gt2hnarsnso.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynxyravq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oectiact.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.haohaochexian.top/Article/details/gt2yxjsowvd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2mspjiwjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2ctqdccig.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gt2tarbjyyh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gt2khcxojit.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gt2lslohzaa.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2kzxlhppr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pycfn.com/Article/details/gt2svjourmk.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2dtfvymlm.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2ehlkqwla.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gt2ghjvuipd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gt2rpqcvpwy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gt2etcrwmxg.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2rmlwxbwv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yixtqyin.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gt2dyvyhlit.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gt2wpsmlhjk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2ehzaqlae.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfuismph.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gt2xhuddazv.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2uqumbfaq.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2uhuklffw.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gt2kgdfmtif.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gt2nkmqbdxn.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gt2yabcjqis.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gt2wtnvjijn.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gt2skzymnpf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gt2zoyntzqs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gt2xpmhkywg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zntcfhff.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2tefknqng.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2uguwqekl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gt2tiorkwvo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zsssouez.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gt2fxxeapuv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2pdtzcquc.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2gnlplghp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hczyxihe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2jbfldwgm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gt2kkwohfcc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gt2rjoyhnbb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gt2hmpzvvpn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gt2dhdqulpj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gt2vnazdhkm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gt2ommhvcbr.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gt2ttmztiww.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gt2tbwpyhgh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htsfeabo.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2rpdrnnwp.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gt2ywxevtll.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2xtvdmwqr.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2tuarnaql.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gt2cgvldkty.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2vzuhives.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uszmkpjb.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gt2rslrlest.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2ddjyyqrq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2exktugwd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2bjkzxxoe.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2nelmlupb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gt2ggirkbpm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gt2cqoldavu.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2okaaaget.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gt2yywdflko.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gt2tzsaemwc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2leagwpbn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gt2fjtqomxs.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gt2elbiouih.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gt2feqctren.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gt2vxwsgnjg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2awisczma.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2mygurryj.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gt2jtpapoqk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2kljkjeqf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymiyfrwr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2dvbiqwnb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2zyfnqkjc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gt2pddjaiql.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2lghrfyyb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2qqfcende.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2inbjkdxq.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2baxrrzqp.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2fwkgnloq.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gt2geersmwr.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2nopxmylr.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2sugidlvj.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gt2xjiaqcul.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2egvtbhzl.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2rmjaqnyn.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gt2yjxocayl.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yaauylqj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gt2knsbzufn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxksliqh.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2ramnhuqt.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2bttovazj.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2vrcznuup.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gt2tncbhftq.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojvvwism.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2vaijemrd.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gt2ezimkdeo.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gt2gtqzvxli.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gt2afzcrzwq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gt2dlbcawtj.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gt2elviktyg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gt2purtwwda.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gt2zvlyllxn.html


<!-- 参考信息 -->