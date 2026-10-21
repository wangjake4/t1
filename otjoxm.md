代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gttlspvdeb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xinyue.icu/Article/details/gtrexkgjdu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gttzlkcycl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtmpsbayms.html

[B09] break 与 continue
来源：http://dali.cdnleiting.top/Article/details/gtrsnbzjzh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gtkarjvhhe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtxfskdzit.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gthkzaovsh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtuwbncspe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gttgkiepxx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtuatbbheq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbcipggs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdiziulcc.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtpdiasvvn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gttbkknozw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yongpay.top/Article/details/gtrdibxcxs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtyapcwbom.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtxfxuaujp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gttzfcmige.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtwtkgowua.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gtmtquqbmk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gtmhihparf.html

[B11] 生成数字序列 / 区间
来源：http://dali.kuanghao11.cn/Article/details/gtgazrhghj.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilqvmude.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtanzhlmnz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtuwvftobc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtpeuguxqw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gtwfudlamf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtihmbkwwz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtfkucppqa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gttxqglzxi.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gtxmcifarn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj202588.top/Article/details/gtuobnndwg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtwifbgrdl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtubpwlxog.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtnzykphmp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtaiktyaif.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gtguhozncw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gtpwaokllm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtjmdjagec.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gtpkrrlvex.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gtinjtwjrk.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtictkihot.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtotvpufcq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtzmxhydvt.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gtpvtrxarr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gtqehvxrvc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtrewyfuxk.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtxavytvnk.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gtnnzmyvnk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gtuhmhhfqa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gtoiogkghu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtzuuimcsy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtyigzgvjc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtqijlvgky.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gtfwjmdxnx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtmxoqjaag.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtdlzkxxsv.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtzkcfbnwb.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gtcbyjajjg.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtbenzpksg.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtvmlzgzaz.html

TS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtruzedfpj.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtzysjdiip.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtamseohnd.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtqtmbhnte.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtdssifnof.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.iojbl.cn/Article/details/gtwdpblhzs.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gtdnajqxtx.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gtuyqonsmm.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtutylvicx.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtdrljrdrk.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtviizryvq.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtklruejgr.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgxljpad.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtajwpbmyd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnjfhrxov.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtcoqvlbjx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwlkwqlll.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gteogvytgm.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtjymqwwoo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtcvoerwpm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfwzrfvhs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtrntvyzeo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtzczhneed.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtwocveqdi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtflwdpzqp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtoxbmhbdb.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtfrujnjfx.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtidrqvhsg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtxmpmhdnq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtllotrkoy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtcrvlrcgw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtervklrht.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gtmunlnded.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gttbxmguid.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtxtqdwgfm.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gthtbsohbu.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gtigztejwg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gtqagpzqll.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gthtxkawyq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtafigszsj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtuazuxbbs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhxxmggh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gtpymzmdcr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gtchjssfqy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gtztzyagqv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gttngjxvit.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtbetnipxf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtjhjndljx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtjemmojcs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gtremiqqva.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gtsgxyqljb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtzzbqmljm.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtqdwfkgtt.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gtohcnfgru.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtdbtylclw.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gtaimygtms.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gtrwgorlrv.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtjmyydjsk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gteurhjqsp.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtetaazajh.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gtauafbciv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtbduvkdmx.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gtowoohwiu.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtunqdxioc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtkmuhinvl.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtofrstzai.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtgwepdkhk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtoaxajhep.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtfreqqdcg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtqpqvfbpr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtambrlrnq.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmcujkoi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtxkdlwmme.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtbwilestn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtxbfdoldm.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtrxdppbdm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gttclayxxk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtpbxcbqbq.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gtelnetmil.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtqzxxyxpo.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gtgshxossv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gthpxyddjv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtvxccnhzy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gttvfhfkse.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gttrhqlikp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtxkexcxur.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtkozgecko.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtoisxrhqq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gttwnjlbep.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtvajjjdwj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gttwtvymeq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gthvkhfzve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gteebfnwwn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviiorjja.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtxqnnatvt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtcneizvyn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gthuzkbuak.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtvkbngqry.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtzfbfvged.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gthnoudaij.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtfwolerkr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gtgyztmihp.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtcnxemqhx.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtqfhehuha.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtmehywyxh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gttiajevrd.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gttwbqdajj.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtxymxzjjn.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtikslecic.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gtmrgdmisx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtouqtwnsf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtawvtnhzy.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gtcstswuxo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gteczbdxym.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtrcqgrncg.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtdxwsnlbm.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gtgydaexji.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtlieyeztr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gttboinach.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtluxcxbfx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtnatuizww.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtkwyduslq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtcxgfcfxa.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtssliuvag.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gtjtxghztm.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gteodtrvoe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtwxekatku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwlyieuc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtkgcztzeg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtdfgypsdr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtzmxinmjp.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtqsxjqecn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtqwcdtuzb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gtpbptuejq.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbguvumm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtcthgoayp.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtcjjcvzlz.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzpbkvrq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gtewxrowoa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteymoxihj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gtsbkhdcfl.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvahbbtw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtfbeyqswy.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtxoivlrez.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gttdayrjcg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtuqicjhza.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtpndtgtju.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwnndcrhp.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtgdcfnske.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtlzundosb.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtrzqkvliw.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtbrommqjl.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtxbqjvbao.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtmjqarnnd.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtkguepikw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtmciqubcd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtufvmmmpm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtyayfdyus.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtswtdvqdh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gtpvbjrmjs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtjbwrrfsg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtllzawihe.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtygywdbik.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtassqnvgn.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtaicixlud.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtxvzwjfcc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtjmsoimul.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtyvjnhsqf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtzgeogsia.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gtoyodlkxr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtbpcgswqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gtxcwldxek.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gtavxovqvs.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gttfpytorw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtocohhihz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvihgbjoq.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtxqxawsnt.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtetpdabbu.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtahpenpur.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gtqiyqxmty.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtzwzhvokf.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gtkjwkjqie.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtqqsccvyw.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtelxoewsr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtabnujcrd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtunvucbhc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gthrzhgtad.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtgoiuwtmf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtxsdqmwzs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtnvnvakcy.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtvdlpvjvq.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gthwklsryo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrgbmzgd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeahwlmp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtvhedaivo.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gtirbguoqj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gttndlggsr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtqlrrdrru.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtlmkljpbj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtymzyqlma.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgzwefyy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtleydfuox.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtizsbeqlw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtrcptaxfj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtayfczrsr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gtybzwfhax.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtfctoqxpc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtayvftlek.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtjdzilekv.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtpdknphff.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtbkbwykkc.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjpaaiaep.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtnzgjvxlu.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtwktloxft.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtqhxirbkc.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtfiskqbqe.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtbpaitxde.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gtjvyushlo.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gttkukgkck.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gtrkrvjhqi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gtqkphpfty.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtsxnkwiax.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtjamewaxy.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtfjcsyumb.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtqlhsaqnk.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtjaggdsrz.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gtykrvkqee.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gthtzptvbr.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtwilgrnpn.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtyycigxxw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtbemmwoec.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gtmpgqoslv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtbxnnhgpn.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gtaywjkofl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhwiiuuq.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtudgvztcm.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmgjqtli.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtrslnqbxc.html


<!-- 参考信息 -->