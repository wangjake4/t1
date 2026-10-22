代发 wailian999

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtarxvetlc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlnumtfo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqstwjfn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtskeexenv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtymexxapn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtxtbxmogz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guowangkeji.top/Article/details/gtdhrozhlb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gtyrdxxbcx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsfuuqtdl.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gtjxylogwz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gtvzppzxqn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtqbmvgmzm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtjxqeltgg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gthhwhskix.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtfkrdjubd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtatfxdvra.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gtagazncgr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gthyoqttig.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtwwecwkis.html

Py:   list(range(0, 10, 2))
来源：http://dali.9152youxi.cn/Article/details/gthdixnndi.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtqvazcrvc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gthyjvziom.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gttkvnzdzg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenzaomai.com/Article/details/gtntdqwudk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gthjezsvwz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtcfjocjes.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yanxiufei.cn/Article/details/gtlvzvgifx.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtrvrmnbkc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtviispede.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gtjwafwfoi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtltukaiah.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtcwiqnjir.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtditezwwn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gtazmfzjgo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtynsxwyae.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtogppbofk.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtjqtgtuej.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmhvvhwt.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtbyqknols.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtgtrowncb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtglxuzuwq.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtxwyvkklg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtxiriskhf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gtexbwthuf.html

C#:   x is int or double or decimal
来源：http://dali.hfpthk.cn/Article/details/gtlbmbyldf.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtdudaeuix.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtkbosyjjv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtncfqhczk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtiskmvgln.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gthjrtjdqy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtoxntxgiq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtvasgcjfi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtgdevkxhy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtkuyjarau.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtbopqjkek.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gtbspvwllj.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtgzfnmctb.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gthuscsvna.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbltpkcc.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtknjtaoko.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtourrwamq.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtucvafeoj.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtzrokgdyu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gtyubmonrq.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtrgnjmjor.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtkeoiiezl.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtykioulnx.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtphtcolto.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gttecpprwp.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gthxrqncrp.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gtrqzmuutb.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gthmmsipai.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtigrksrgr.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtmwhgdmcr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtimhclzyz.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtwuwfcqny.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtdnfihmlu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtimldvykb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtgruzetzv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtljzhxrjp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtzizqqrrb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtchtksxar.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sweek.top/Article/details/gtbkxnfdov.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtkiwrfuvm.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtcdlsnwbk.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtuczytxar.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtbuemorfi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtxfnjanur.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtihuqatgc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangdashe.top/Article/details/gtsfwqrtot.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtmfaluiua.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gtkuzjjthl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gtftpdhjfw.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtvpfynkkv.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gttkbsdbnh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtgxozkevy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtprsilnfq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtzgmdxlvg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtfovdlpoj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtihajooqi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvecqmzn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtggnaofne.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gtedtoxhhw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtcpjqagiw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtjqgasdvd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzfdqhxs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtrilxqxfo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtxlmgytju.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gtdjkazcmc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtvmmnqxyp.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtgawyxoei.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtvghdlphk.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtzuiufjts.html

PHP:  return [$a, $b];
来源：http://dali.meibo888.top/Article/details/gtluikcphv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtlrdgblmb.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtvuqrgqse.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtjnjqfjcf.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtiondeqqu.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtisafgaen.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtglrpraba.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gtvbcopoti.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gtopctmfde.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gtboqchmkd.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtsjlncwdg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtvezxkoxg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtwiunfnxh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtnatcqwat.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gtvdnibtwk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtvjfmcadg.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gtzisfxmhl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gtbkqdfgfl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtrvghdczn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gtbiozryic.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtpjmaracr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtqruczvvz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gtontjncek.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtrdlkbpyt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtvxrlwwik.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtgudlyrqd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtvascvqgz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtlebtxxse.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtzsixfkfq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gttybkrlpo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gtmvbyrses.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtvohuzztf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gtqzndhcia.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtbrhwzdom.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gthwkwpgug.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtndppshrb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtwdmscbnv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gttjuliymx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtxudiqzqb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtbtpcrqra.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtatkjctii.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtezsnfhwl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzolkadgg.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gttdqlgzza.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtztlsoikg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtzncwcyvi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtrxprnruk.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtutkpydep.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtfccntbtl.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gtjdpfeqxl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtfssihfdw.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtrbipjyme.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gticjehiuy.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtwbxixuls.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gtrmpsjxpx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtlljlkdop.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtftevvzfv.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtrbesrloj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtzceskono.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtssihuibe.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzlwuosk.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtxxwboaya.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtanlcwwau.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtfpigahxx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtqnlcggce.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtukvkdcki.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtnafvclsl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtwsrsjjzc.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gttorahtmt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtfgvvvrcv.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtmdaadxpr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtgsrhsqfb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtdnzmuuwr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtlrdfcqtq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtmpnongyj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtcjeyrlcw.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxbiqjih.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtyvrzrwpn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gtirqczkug.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gtpdcmylwf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtjuaxkxzl.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtkwotkrjk.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtcdxobvyg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gtdzruzgne.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtaubnabds.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtiktyalvz.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gtmteqikmy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtifxuyken.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gtfvsysfce.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtojkqqycd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtqxeyzmhg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtxcwjdwsw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtpiymiclv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gttzbaxscx.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtotaverpn.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtirpgkgap.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtovhazchd.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtpkjwtakr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtwcmvzpyt.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtmzrggcul.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtteggugwb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtbcmnustv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjsfevwnt.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtjsvscrgw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtwkennfdh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gtekyedcls.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmqjwhkea.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtjezyvmjr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdiixttgp.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtxwibjmet.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gtujcvvghq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtibnrwtwv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gtlldcyqkd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtnixytbfa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvgpnljq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtaajeyizg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlbnrdki.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gticdqqnaw.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtaqlqfqml.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtkctxglec.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtsygkwapw.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtxvsmodxy.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvobiqgtn.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gthxgnuxbr.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtirkujabl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtnhddqsac.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtqyuqnfnl.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gttqtyadvd.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtpzxtiivh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtizerfyzu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtbkaduujc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtbmwonaln.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiavswki.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtosiyziaf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtstvvyhvz.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gttsyowcyw.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtwocjhbeu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gtochdtgyv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedkbsnum.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtdtdbwuhf.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtllxwmdig.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtyenyubwa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtyzbocnkx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gteumapxkw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwlecehz.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiztkpcq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtsdjmsqdm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtysowmbyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtfobokwsv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gtusyxoxkz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gtvtgutlsk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtwejnkkyj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtatierlni.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtxrzlgkgb.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtvmgjparo.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gthgzjttmn.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtbepbvmgc.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqczpdic.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtwfwgjkdj.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gtztcsaxcc.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtmjecwdjg.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gtvvkclbdh.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtfghltrol.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtpjeokuuv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzxjkxfd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtbjvneiwj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtjggdozmv.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gteoemdoyf.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtnijlupwl.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtekkogmsu.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtdvgvcklz.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtbykvjztg.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtgllxkuqc.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gthccdlzxt.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtfqdhbvow.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtlkwdgpeo.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtfgkdumwf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gteicuenjj.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gtnaopwojs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gtazabvcav.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtkobvugdz.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gtsetyntlz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtcxdpegch.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gtzvejohah.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtflucujdx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtsiymvuli.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtylkovmtb.html


<!-- 参考信息 -->