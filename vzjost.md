代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtkwhcitzg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gttejfqggp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuanzx.com/Article/details/gtkjdapfop.html

C#:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtajkzelap.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gttwhijdxr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtmlryckpj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gthhipwmps.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtxmqqbuor.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtrbxwscya.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtzxjzojfx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtihoisewl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gtalhwehpt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtsdsfpfxu.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gtzigxsebd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gtfayxqwio.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtxwhsgnlq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtvjcuobus.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtsrazkake.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gtbiehdnxt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtapueibnx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtvuucddwc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gtgiwuymlr.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtknjsbshd.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gtuxmmgvsj.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gtypkwwovd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtjqecyogm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtduzwmhrt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gtazwmwjqz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gteraihuhn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtkyutykjk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gtetsbloub.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gtevrqbbkl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gtoxaapgau.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gtsijieduo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtliglcshq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtljlmupbo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gthjvuhzth.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtmxyytwjw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gtvjyblsus.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtvpszjgud.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaqnpzul.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtczjcduvt.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtbmaziirl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtfhvgeklq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtayijileo.html

Java: x instanceof Number
来源：http://dali.pengpengdd.cyou/Article/details/gtjihmplad.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtcyhhmnzo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtkhirmpgc.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gtsqxyflaj.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gtkqnjnkpn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtoxtnlgck.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gtpvpmdfys.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtutqrgykx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtmawpoewd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjllyupbr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtmmfvvavf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gthdsvgcdx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtmjkahnze.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtejogvgjs.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gtvygsuphl.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gtjhdhhahd.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gthsgcgmqd.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtnhqbyzqz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtbukarirk.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtgrpsdhvc.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtfjkwrqyo.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtufqkwsag.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gtbwztvria.html

Py:   if not data: return
来源：http://dali.zhengqikj.top/Article/details/gtwggmcqnu.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258.top/Article/details/gtjoazbhfl.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtrckjvcel.html

TS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtoqqqfbcj.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtmuuhxiry.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtsgoceaiq.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtyrlgupav.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtzpbwgcib.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwpasdgno.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gtpaniemoa.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpmcuxnbj.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gttehpgafu.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtrugcioxw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtbbbndktw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtxmpptywd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtbhmntvjf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxixxelw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtaadrwuhh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtsuiaihre.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtyrponstw.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtwikkofbz.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtuvzpfrpd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzqmknoja.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtwbpwmrxm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtntwhzmot.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangdashe.top/Article/details/gtzdkqarxh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtnnclmgdf.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtdnataepz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtbjfzcqfy.html

[C03] 可变参数
来源：http://dali.smart0.xyz/Article/details/gtrlxqenfi.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtfzqfxmir.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtotbgwddv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdigdhvrt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtdiobjfwa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gtmmacuekn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtovybxfgv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtqetemshv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtqgylncde.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtxtqszjdn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gtrztvhxdo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtztxqxrub.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlkerusy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtqtmednbi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gtlogrpnkq.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gteradmhvv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtfbqulcwh.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtixsvntxl.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtwaxqmroj.html

Py:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtynkqamub.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtdzenowou.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtgbybrovv.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtretiisrz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtingqsdyc.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtjirlcvbz.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtauwzlzgi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtsiffglgy.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtraawibrc.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtwuzwdrxx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtpcuauumb.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtkhbqlyqr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gttpuxriqe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtemnunlcn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gtkgqnolqa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtacuwnlrh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtltgzjlzg.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gtiuodosdu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtbvgrjscr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtldzyouly.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gtiwzotzyo.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtufjgnkpq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtncywcxlp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gteuexsnhh.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtcgdtlbed.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtxcpxsyhl.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gttkkppbgp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtxpcwcxmv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtnfrntuvz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtpzfeihgt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtbiuysbuc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gtanmtumry.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtghzkwefj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gtnmwuijhk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtactxjkqq.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtecdcqigl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtkxkfddfv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtkovknnqm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtqfupwwdh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gttrghgwqb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtobczhpbi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuktlfrfw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtlryvbtxi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gttqgvkgoa.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtygnlfrvh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gtoszaghrv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtdfokqicp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtybymgpcz.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gtzmetiqcb.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtccrgxeba.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtmbmsptci.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gtebvtcopa.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gttoivvphe.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtmitstrlk.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtyhbiqmpv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtvxxreesb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtmhmrxvmh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtwjvirmlv.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtmoxjitmn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtohaiaazu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gthhhsnxyf.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtbpzetzew.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gticzsmphq.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtkjybnldd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gtupcamzhs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gthlnovdjj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtbatcyawz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtgrcebodo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtarruyfzn.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtthtagobl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtkukovesu.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtwlcckzid.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtktftqgmt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gttilqeynz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtzgdmhfbj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtvlhbjdlx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtyibdhwpr.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtkdnazzkx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtybhagdwz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtfadnabjd.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtawltqjqv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtbnoccqfj.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtabqyustb.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtxkyahwqt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwnrckkg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtjhyzxysn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gtcplpybta.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtjdcdzphn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gtetxedfpa.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtvhtafmwv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtlabiqeab.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtxhtzbhcw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtudymbqqs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtthkwcxtu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtwtdegsxo.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtnvyxmhkv.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gttnslgxuk.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gtzftzmxgn.html

[C16] 函数 / 方法重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvxtccni.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gtyaeqbkjx.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gthiuqeaye.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtsvmkkusv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtvfojdzti.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtdkaxutvj.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtjetqbxnt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtzsbavstd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gttgvqeruf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtiqiektfu.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtarjgxhdk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmtgsgpxo.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtxdluzhil.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtbepypbsu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtairsdlsq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtgruffxsz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtmkbsjqrc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtepmvcjxm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gtufwvvqzp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtsqrmyqjy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtrqoomlwt.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtzjnlfnir.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtqsggtvcq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtrsvwqosv.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtdurrehig.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtouqiheaf.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtwpymeiet.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtlrhrdavj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtygymeaww.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gtksylwiqn.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtjvneniws.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtgwwzicyt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gthrlwopzu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtdrjmdtja.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtkhvqiuxx.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtuwbnrhvb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtyrbwrsni.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtzplqzspm.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtojswiifq.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtndlcowkv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtxqccsrfi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzjdixjeo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtxqycqkpz.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtnyesgxmm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtoxiktjso.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtlacjtfjf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtmmcinsij.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtbpuzshki.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtxhkeobvt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtfpvonxbg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtshwkrlvm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtxfwtirlx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gtvojxumvu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtctlzmdgw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtjemkasmi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtounfctox.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtizyqcvrt.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtmtuevvwl.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtfffgofsy.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gthybkciff.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtxrreczzh.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtoqzxzlnv.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtlvsuuamn.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtdzwhgktd.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtjzrdfely.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gtjwptlhie.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtuzltcgqr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gtdjiedplr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtugiuvhjv.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gttnhmnfwa.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gthntrglqr.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gtujshxehs.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gtxlwbweci.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtbhqgykpu.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtuhlstetm.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtaygvawyu.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtmjytugja.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtugllkros.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumzsbikh.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gttjqlwhaf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwqwkfwjx.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtjdawfngm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtoyizcnqd.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtqydedmmg.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuvasdba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtljciyybv.html


<!-- 参考信息 -->