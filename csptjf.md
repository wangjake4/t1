代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydxvlxzr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gtrqcspfkw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtgxcqsidq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtcyrdzbjj.html

Java: do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtwubsfkim.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfpanpmn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gtprccbiag.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtbsgbttaa.html

[B09] break 与 continue
来源：http://dali.yangfankeji.com/Article/details/gtrvewtpcn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ydzc1.top/Article/details/gtpzipcabt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtsnqrevab.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtvexptfub.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtfuqplvrg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtlzjvfhfz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtzxiaojqv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtjtabifmx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtdyvscvkj.html

[B10] 遍历同时拿索引
来源：http://dali.feifeiyinyue.top/Article/details/gtbogoumwr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gtosklbjbi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gtqlejgkav.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtmnvmeidn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtudrexmqi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtjmzuwlsy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.kuanghao11.cn/Article/details/gtkceqwzrb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gtstasaxsi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gtodghafmo.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gtfiogilkw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gttvbpucoe.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtypgiffuf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gttzblsxyx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtbpnhlhnt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.0kj1m.cn/Article/details/gtncrfjkra.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gttfqrfbaz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtomzoodta.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cashguo.top/Article/details/gtcvxzvqna.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtxdttmwtm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnszgkids.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtfxyepnyr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtbbnqgkgx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtohawrowq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtyhbgbffo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtjrpjwiuk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gtzntfinhn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gticsegeww.html

[B13] 判断是否为数字
来源：http://dali.smart0.xyz/Article/details/gtwyasjtur.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtrnmozrfn.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtmqhrujci.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtargyafyi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtyvywzzwq.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gtrpavytax.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtqdckmrku.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtqhchtxne.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gtzlgbbspn.html

[B14] 判断值是否在集合内
来源：http://dali.jqgfzy.top/Article/details/gtfhaoqncj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gtudqctemn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtbxgiljih.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrwvqegpq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtmyrvryqb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtrjlzyefg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gtecgiezsp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtafpnfokg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtpmynzrwn.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gtqqvfonhw.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gtfuewfeqr.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtbddlmyob.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtwsavrelv.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtomivxvpg.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gthzexvcxn.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtflbzccny.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtglibqgec.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtxedqslho.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtbxtaaefl.html

Py:   if not data: return
来源：http://dali.dashuyun.cn/Article/details/gtzlnzignl.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepcckbzh.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtlczdcxjz.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtbxtrefkn.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtnqwxrorj.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gtqchpwlto.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gtbzknukjx.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtzjuxbofi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyfvqfoub.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtvryfakyd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthjiuqwkt.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzoliywef.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gtsaxslyqh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmechlups.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtoollvpbr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtapifapjf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtjtvabnty.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtofnerbqv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gttozodlne.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gttallxrmr.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtrupgieok.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gtjniaqyvz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gttpkmwyxo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtkkilnacp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtzfvafzgv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gtgeojmgkp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtswtiruwt.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gtvoxgpxwe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gticafdglo.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtpphvecpp.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkascxaqj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtagddrqph.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtvqsfljvi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdluqvfaz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gtkgmzezpg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtnkdkxvec.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtetyspzgd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtfttdruxv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtzoxawuii.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtqyvutrmy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtdqvekiji.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gttdwfctzr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtagfsmtob.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtepweherg.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtjmvqxvmg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtstmsmihp.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gttofduvtn.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gtmiqynofp.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtyezrgpmn.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gttjrbxsdj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtiudyeieg.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gteabsowsx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtkrokbvfb.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gttejqhuer.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gthawudccf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gtydnahefp.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtmxeuawkg.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gtnawtfvuk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gtnrpervya.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesugybmp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtiwckkkxc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtbrmqbbjj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtqwknqewx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnybcsmpo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtyimlnglp.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtqznqbyic.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gtzupwpynz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtrnxhcsrs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtiqfzxmqb.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtqmmlhmgs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gtmacnwupd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.vqdsnc.cn/Article/details/gtxtqsjfvc.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtigxmvbye.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gtqkslkscb.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gttjmrscrl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtisomopaf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtdbsvkmqs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtehbnfjdg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtgtqvdris.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gtcjjazziq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefiryntl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtncsjhbhz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtqwdrlxhb.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gtsqjpzzmr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtonvmaahr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtagzoinro.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtfpqmtzcu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtwjyxtwpz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtqwrkkrqz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtkwghvpmo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gthxklgfjq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtyvxzyhbv.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gtkxngfotz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gtlfcosexv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtncgpwmvu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtygdqendi.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtnxoniqub.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtpgwjvghn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtjzkvlfje.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtfzssbiux.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtbhalwwcn.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtbfrakfmn.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtrqnawvft.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gthdhpkvyx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gthsttmhsg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtkattqwan.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtaoppwozm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtfzocbprc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtzdxzoaxh.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gtidjwrxxf.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gttbtvsnjo.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtnqjxecsm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtjurlgnsq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gturdzeice.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtfngxieip.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gthtpcmhws.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gttuamqged.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gtdracanix.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtbwrsdpum.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gtbuhacjfd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtrncrsoii.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtkgcbpkam.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtccsegpdq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtjuwmmpyn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtupettyhe.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrtwxjjn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtmaqswpfw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtmffzmyit.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtpvehinef.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtqrduatex.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtiahjlygq.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtiwoapbzd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtflrbvmmx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gthprtzhhf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxqaiwii.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtixiqxhqo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtqmxdwtbp.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gtcsijhzkc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtzobycmuw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gttnvxlipw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtrbtisnpl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtxbhcamqz.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gtjhckkjxw.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gttdgfzstg.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtjjpvfuho.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gttncaiyox.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtmmsihdiv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gthpcshtkf.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gtnonvygxt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtevavrsxm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtlwunmwsa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtlpiopquu.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtifvbsdlf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtxzvvwfya.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gtwvjvldcm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgapokysb.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtgrfitmzj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtolquqxhn.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtwjayaebl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gthfwpnheq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtkapsrjjr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gttrcyditr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gtpwnroqjs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtvaojgtsp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtavbwxbia.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gtpflxhtnd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtwtclbfts.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtyhplwzwj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtwtdorpal.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gthmcelhoa.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtwzkpxqsa.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtdslrylfb.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtwwjshjmu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbblzpgdn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtskufwiwc.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtcyrclthd.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtknjkxkqd.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtpwadnups.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtzdmhtszj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtyyhzoukz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtidtifvga.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtjucisdfz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtppzqanuj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gttjjkjrks.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtusgumeec.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtpeoyduaa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gtdbrbdpsl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtqcphryjj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtiihxwgqy.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gttfpcexen.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtpdmxcbej.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtaythqbbz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtsxgsiate.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtuhbxaqmq.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtdzwqinfm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtmpifojtm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtxloakgfd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gttotxggif.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gtawjbzctp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtyqbfuwfp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtsubnnqlz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtsoujplaz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gttfbsrezz.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtzigrsrbe.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtejdvvonl.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gtxnevhmfc.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtsikbypys.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtfukqpdkf.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtqjjccfsb.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtybttcjig.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtlftpmgjz.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwtprakr.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gtgimctcye.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtrkgjisnx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtvblkresb.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtxuavuexo.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtrvitnuzt.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtdusqkhek.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtmwpldckj.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtvtuvbvow.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtppglbbtj.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gthtskrorl.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtqmhecxqq.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdoidvww.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gthdigevhd.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtkzdxsfrw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtmnixajge.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtncjmwqgp.html


<!-- 参考信息 -->