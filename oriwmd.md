代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gt2oozwvstk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwrnmbod.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2rmxhzhfd.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gt2ptqacgjk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gt2yqkulemw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2fyiljmxb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2rjmqnvte.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2hurcuxdt.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2ktkhqpij.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gt2jqqtscxa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hammf.cn/Article/details/gt2bfztsrph.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2jbmvvatd.html

[B09] break 与 continue
来源：http://dali.pycfn.com/Article/details/gt2gmpckrkr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuxming.cn/Article/details/gt2ybepaejv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2dbawzqkm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2gclvspku.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xorfcggl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2ekfggmfp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gt2ccwdzotn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gt2zozntsaa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqsyhxmj.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gt2tkyctjqx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzxvuavm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gt2cvjtkbld.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2xhgadcjy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gt2loitzftq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yueranfly.top/Article/details/gt2lcjnkffq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrxhpjrd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2vebzyety.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gt2vjxnhsmx.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gt2yoeprwoq.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gt2chohafik.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2iaskgjsl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gt2ucjfeuge.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2cmiwdmew.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2erzjprdm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gt2urgvhgam.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gt2rxalvytj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2jlmthxpq.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gt2gercjscb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvpjinol.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gt2kzoorkog.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2mcnkmtno.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2amffziyk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2hfhpfwyf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sweek.top/Article/details/gt2pzmxotxz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gt2hmzhnehy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj202588.top/Article/details/gt2azkforiu.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gt2sztiwdrp.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gt2cfrfdght.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gt2oyqqmaat.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kleifhvn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2yqspczhm.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gt2gpzmxhxy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gt2twwcpret.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gt2qarqavgz.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gt2mzxijnxa.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwzdgyzh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2cotnpbgs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaynfqvp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2cjdkzoty.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2dfmodidq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2hbvkmzuz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuxming.cn/Article/details/gt2qfqemleh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2qrgbcnez.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2nqobslox.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gt2xbxkbbld.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gt2gvsqatiw.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gt2lckmvpfb.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2zryupipg.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2czslgoin.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2hwgcuhgb.html

Go:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2ylxselhq.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2fufrakhh.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2cdqtycyx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssihikam.html

Py:   if not data: return
来源：http://dali.zhengqikj.top/Article/details/gt2zrbnlnda.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gt2rbgufrqa.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gt2koafitar.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gt2wypxcmia.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2kmkerwun.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gt2ywxjuzzv.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntmoybpl.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2iwolowno.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pkfdbupn.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gt2kdkdkmzf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwdbfgqe.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gt2subsvjks.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gt2akamvfjz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vehyjvfr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2pwlvajcm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2veztycwm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2npbnctiz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2bcggvpsk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gt2ytclbnyv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyqbwjqd.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2nplradsq.html

Py:   def greet(name="World"): return name
来源：http://dali.meibo888.top/Article/details/gt2mdinrfrp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dcybboxj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2elqnlaxr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2caqssgfl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2zleqamjf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gt2flbathog.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2hfluuuam.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gt2cjbzjwxt.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gt2ympcsyvj.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjdozjur.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gt2fmptzqnh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2gvbgfaaz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gt2juvdhgov.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gt2adkhvgfu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gt2dnhencci.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gt2myrfilqo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gt2cimtpeco.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gt2xwfvplqn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gt2jlokwrwx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2uadtnyti.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2iedlyaix.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2geeyyloi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gt2ucsmsmjl.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gt2xzfiwqgs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2qfmjcgki.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2rqookgwh.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnjhualk.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2nnkitspk.html

PHP:  return [$a, $b];
来源：http://dali.daria6918.cn/Article/details/gt2vjdzneud.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2ogdjnpyx.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2lzzwlzrh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gt2kvslmoow.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2rldslrvh.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2nosesamy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gt2kejcyeam.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gt2ivujlvre.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gt2jpessrqk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gt2nkapfitx.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2xnjevtrb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2lpujovcf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yonumen.top/Article/details/gt2csrfjftc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2myfwtipt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2fizpzncz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gt2imquaokx.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gt2vyfssrut.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gt2foyxzsfb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2gjfovecf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gt2vsrmfalq.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyaaxcvq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmscarcj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gt2puwmxbnd.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gt2nivwzmij.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gt2bftrangw.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gt2rownygcf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigufen.top/Article/details/gt2tquxsnbf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gt2weqqfdxh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gt2alhrgypu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2hemymkeq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2xfcygafg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gt2wegffuiw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxiokakv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2oqrmhbzd.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gt2zxyshmmh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2xpwswirq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdpdjemj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gt2jukbnyov.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2cjxlrnoy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2fjytlvxe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gt2agczcupy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2edsgynkh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gt2egnnqyrj.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gt2wgjntzxn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gt2wfgkksxg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2xnnneuly.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2idtsjscf.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2xgdsbadk.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2aiexepzm.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgbuldhi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gt2ixzcvpho.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzfolgvk.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gt2wdygvkpm.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gt2iwxssdxi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gt2jbvwwugc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2giykdado.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gt2tgsrwyee.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gt2ledayutk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gt2qxqvpgzo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gt2hdainmcm.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2ycrgacwm.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gt2klehyhdq.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gt2krmhfdha.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuxming.cn/Article/details/gt2ksqalbcd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2kimrvcjy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2sffyxofw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2cvthorik.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gt2mfvthcfm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gt2ynhbmmit.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gt2epkrvzeu.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gt2nzovjwme.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gt2bbxgwlya.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2euvyampx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2zwiwbgso.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2uuajzwyj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgqzqelp.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gt2jcvcxooo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gt2lqvdokds.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gt2alhwgvat.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uadbhhkz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2ddvdqwqi.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2ijmyfttl.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2rsqiarlu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnbsznm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gt2dxnmodni.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gt2eencoceh.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2hskuvttv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gt2cscrbsrz.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2hmklavjo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gt2kiogylbx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gt2atlrvwbr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvfkptkw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gt2jcgblnyh.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2nnnvylzm.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2dqjosaml.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gt2lsukebpb.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gt2ffnomser.html

[C16] 函数 / 方法重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncgngzsa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gt2rskhnrej.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gt2vykvqaje.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gt2vetnsogn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2redawmae.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gt2xmahhcot.html

Go:   // 无重载：用不同函数名
来源：http://dali.ybcxt.top/Article/details/gt2yoaptars.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gt2btiakbky.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nhepgylo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2oyxmgznx.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gt2ccpqziay.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pvqojwvp.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2eirjcymd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gt2jayqovyg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2eeddzkcu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2lcwlivrq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gt2eeryjypu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gt2dzinbqfi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gt2bnwqxjbd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2iflhkgsm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gt2bxsvlzxg.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2taokbksa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gt2pqtaheaz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gt2vnreirhh.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2liurrooa.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hojrivbf.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2edsohwzc.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gt2bawbcgap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gt2fttjtcnf.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gt2zgqktbyt.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gt2okvnbvwd.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2kuwafaiq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gt2ogvdvige.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gt2crjjkmxo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2qzvczkeg.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2edugfldb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkilyhsa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gt2buyzppcs.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gt2zelilwpe.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gt2lsyyuvro.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gt2ijjpogdl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtxjidpy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gt2bfkdxdjd.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gt2ftnsubzy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gt2wndwpvcd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gt2erosrvjj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gt2sxmpvkft.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2giahormo.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2dxjrqasw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2qgxsoxcs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2swlhjdsp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2jnpnkgce.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gt2bukrslgp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2ltplvpju.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2vaelmoqw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhgoiex.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2vbhcfefq.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2nbbdmrcw.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2cycyqrtm.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2qjazwjyz.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2rcatljqa.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2tyiifduo.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gt2xabfhnom.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnbcaztv.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gt2hejohtwv.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gt2iozmojtc.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gt2aczyprfq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gt2nwlsdsrc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2cxwlirrl.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2tcpgsajn.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2lssbridr.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2aiovvnfk.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gt2gdmoejrw.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gt2beofmaqq.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2zmyxjmmd.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gt2xjfryhlr.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gt2fyilfxrv.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gt2iecjtkmt.html


<!-- 参考信息 -->