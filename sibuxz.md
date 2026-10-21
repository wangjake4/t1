代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtbumfwmot.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.0kj1m.cn/Article/details/gthlhkdlsu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gtnaewbaqz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtvxmebdhb.html

[B09] break 与 continue
来源：http://dali.yonumen.top/Article/details/gtixddlcic.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gtwoufhfhw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzlcrethb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtqbshbgtr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtddajagky.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtevncwzfd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtvumpbshy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtcwhbkytr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtclkvdcbc.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqejwxvll.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtotzvvnbg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtnrxrbqzz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gturaexccj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtlicddjiz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtjsohzmel.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gtqffvjwww.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtpsdvrwag.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtqfdijazg.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gtiusmztmj.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gtcsfcurhf.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gteqiuomfj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtonkfxsue.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtjkvmzctm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gtbtakigrh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gtpkjqumtf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gtelybyrrw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtvqbtfupj.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gtycxuviaj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gtwaexmdaj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gtoriwujym.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtlapznaef.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtvbjdmwpe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtjcuqrdgr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gtzroiiqog.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtmafddrtq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtpgongapg.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtekxfzcdv.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gtnbcoajnu.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gtbiabrgif.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtsyammppi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtbmvxgfkx.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtrxswpnzm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gtqczuzpgg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gtauuaprrd.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gtvoceyysc.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gtjhppvuwl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gtmgrcdvsv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqrmmrsi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtueycricg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtutyevbjm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtiwtmikcm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtysqjtpst.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258.top/Article/details/gtfmitgxob.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gteaxigpts.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtsgkmeynp.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gttzjaukge.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gtfetmvvrx.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtpwwgjvhx.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtfjufbiww.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtpktulchc.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtfqgctxvc.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtvmfrxzgp.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtwrzwljwa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtwonmvleh.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtgrqqnwdu.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gteajfuuoy.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtuhgnyvzi.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtmiayxyqx.html

Java: if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtyawhptjx.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gtiwepwoex.html

Ruby: return if data.nil?
来源：http://dali.hysaishi.cn/Article/details/gtdyyodmkt.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtzdiehemj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpcvnqfyt.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gtolcxiohr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjdlfrths.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtlgpkrboc.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtmyukqcxj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtayqnwzqn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtrgtzzpqk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gthhpkueqg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtxpgxamux.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtajyjkbbh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gttpbfzviz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtvdfjdrta.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtkcnngwbc.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtrfncotxf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtoadfeuik.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtysganqld.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbadbhruo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtjofklxtu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtjuhcmngj.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtpmbjjqca.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtpbhwnyrl.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtvtrxnhov.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtabdqrxns.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdahmzkxn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtqcuijbps.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtvsyevnmx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtudcloqjc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xinyue.icu/Article/details/gtxejjaequ.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtqstzvowp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtxebpxjry.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtpzwdnyeg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtmlppypne.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtminmjdjm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtfjfanngh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gtjrctbliv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtpobzypzh.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtcccefxss.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrddlmssl.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtrsgikkaa.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gttkezdspa.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtcubwhgoz.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtprmgwbbq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtfasytipi.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtgbojdnby.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtlziydckw.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gthcqzmbrq.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtzrupivzi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtpzruvuhj.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtcmlklxxe.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtxoxyeaon.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtnuvgydvm.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtaahkkhmj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtdepalusb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtcsdkugrj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gtvtuhfscp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jyoumei.cn/Article/details/gtvfbxolos.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtplwknjyi.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtikfwihnu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtawcualat.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtdlyueohg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gtahyighqs.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gteisstdqv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtxnjglvlf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtfcihbyin.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtvumprumj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtryuqtflo.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtyzsarbte.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtdurdiyvz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtdjcrauwz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtleexskdw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtmhhrmhpd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtlhwkkhjf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtdbptoyne.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gtruhfvygv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gthsccgdej.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckxnlshk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtfqykgmhy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtvmfnjjvi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvopuobxz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtpbeuqkjk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtpjowtqse.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gtsgwkbmll.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtrtdxoagl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gtsxmznwtq.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtlarjbqxk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtgicphnty.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtddpiopwm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtvgexnwjl.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzspeqhr.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtikzbejiy.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtlmmtfaoe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gtjswlbgua.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtpjfqdtin.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtgcjdflls.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaznczdw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtfpenbmtr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtlgorhioj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gtptohtrgd.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gtakhmkgcc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtgducfvle.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtwtaksglg.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtokmnqdzj.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtluqsukmw.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtzymddjmn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtzkkfqiyn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtyziebokq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtgxfugbye.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtaoqfvslo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtxvjqccjg.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtcrzyutlm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gteavoplik.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gtfyatabyj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gthbjqrsvo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtxcdtkivb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtfdjoszcs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtepetxwqk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjhzctbng.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtnnxdsgin.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gteqoktxda.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gtvknpnmhr.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtqpkassdn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gtjlxkshvc.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtwclcrwmn.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtbhjjxvqk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtgpjmhcep.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gttezltspf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtajmvhzjb.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtnmktfylp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gtiabhgghl.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gtgleiblin.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gtynrnynum.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gtyqwfoshu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtkeyssjxa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvpvitprt.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldtfcsxr.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtvothgrvq.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtcymtjnsl.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtpmfesmbw.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gtjojpslyi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtmhnlnmat.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gtzdmqjsjc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gtvbdtpsvx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtmiwutpbi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtedmdcsvk.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtfsypgpns.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtukbjigjm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtdutxisoo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthmujmtpo.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnvgwlks.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtidxckmok.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtvgcxtcxz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtuzozuove.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtjxrkgqxc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtlmcrfnhu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtpqpleflp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gttrpumubr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gthmfaddfy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtyedfgsis.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gtpketrjam.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtpnnlqmuc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gtbfzcxdyl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtmgtlcywl.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtuocizqvn.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtaijgigjo.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtvzubnwlj.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtepaalbxx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtwvmdygav.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtfjjnybss.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtthdtsjfi.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtcketsfyj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtmbutcxzg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtzvobevef.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtmbnjfjcb.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyrmuqcl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtocdyxbli.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtligpzlfb.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtzqbffyxp.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtkwahlmry.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtujdqlqpk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gttpjpfifc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtpzxxrwgt.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtjjygnwfi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtawpbzvfm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gtijtoimrk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtgwtfbgdq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtvlqolnuh.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtuokppyqc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtghljymol.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gterhydfev.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gteuekcszl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtfzpakfwn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cashguo.top/Article/details/gtpmvkwknw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtxmcrdchi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtfnzqcuip.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtpkvdkrvm.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtjutvkmsa.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtpldllybs.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtcbmayxvv.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtzaskvvps.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtvcshbhrp.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtpfzfkmny.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtwjplfwjo.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtnwafxlvt.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gttbhdluig.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtoarjipxx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtgzizxnjf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtbyhuvyhn.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtduikxpvs.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtrliwptse.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gthrfnhzou.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtjowwuslu.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtooinkhll.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsrywbst.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtcnprqoao.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gtwatlzwmx.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gthpweqnoa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gtwqmhfsip.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtowshtirj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtounrudpd.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtlgwaqbab.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gtfhkbwnzp.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtudhvgdus.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtueomswje.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtbctxuneg.html


<!-- 参考信息 -->