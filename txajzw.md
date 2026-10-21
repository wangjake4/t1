代发 wailian999

[B09] break 与 continue
来源：http://dali.chenjidiqi.icu/Article/details/gtavlkbpew.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.kuanghao11.cn/Article/details/gtxshmzabh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtuvatwvdp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtzkdyfckv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtipppjnut.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtsjeqnlhv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gzhubu.top/Article/details/gtinzotxvn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gtpdjqvxjt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgrxuoki.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gtfylrbftr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtrysraldh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtczgucfvj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gtvtxxeesz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtbquoxult.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gtskyqbinz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtifoeetbt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gthlqkebax.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcsbuiaht.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gtoynpbyhm.html

Py:   list(range(0, 10, 2))
来源：http://dali.bjfxy.top/Article/details/gtxxdxcbwu.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gttpuejnic.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtknafscbl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtglrnelyw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gttnhinlnu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtpouojxgc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtybblvhfg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtfuvbqzug.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtdfxcbgse.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtkanozzsc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gtitppwgsq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtjirkshxw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtjgxkcyjb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtrupnbmut.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gtcexzarny.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtinebztnj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtefgbdimw.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtvtkneosa.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gtaulshydc.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtmazwnsly.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtfxghqajd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtnuzedlfk.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtpksrhlqj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtjwvlqkdu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtscihtjmo.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtttklotoj.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtgboeahja.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gtciztwudx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gtyzonrqra.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gthhowwsle.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtnjfhyxtr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtlcwdogrd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtcbiivpku.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtspbbwlsb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxxppsxk.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngemxswl.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gtogqfwtdw.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gtbajcqoiu.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtjamvsljq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtohnriccc.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtyamrsskx.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtascotufa.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtgpqjgeal.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gthmkjbbfq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtubvxphbz.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gttxoofpmg.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gthqmzsljf.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtolfqctyx.html

TS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtzgrsjkai.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gttuwnfcfk.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtcorqmhyi.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthovntpih.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtlvhsyfpq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxapisuoh.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtgzrfalhg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgxillub.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtjzjbbopm.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtbhnftwfz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtcpcvrvny.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtthewmdnd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtuwinfowy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtsaycmhrp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtcxarfwig.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtvxjcuoiw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtwjhrznce.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtuqfkwbgy.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gtasegzqsn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbzrgjkcg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gttrlqlcjg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtubdcefsr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtokyuekdc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqxuuvtt.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtpbhmcpbf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtehcayxjj.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtwtfpdcnz.html

Py:   def total(*args): return sum(args)
来源：http://dali.nwbrower.top/Article/details/gtayeyermq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtukphhdkw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtooojazhv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtznjbffxq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gtxyezevma.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtkszgksyp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gtbgdadszf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtxxdnsgyv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtjfoegfiz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmobzdwhj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gtaoibeavo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtszikvclj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtprchdhmd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtuflcoomw.html

Go:   // 无：用配置结构体参数
来源：http://dali.tanke756.top/Article/details/gtifmfqqib.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtjpksuokp.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtpgmhcxdi.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gtjhkgecnx.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtbimlrqnv.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gtwhztgwhr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gthrfrfnwc.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtjeqkxeai.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtdkmrwvpo.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtdlmhfuck.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtaijklgbu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtszpothmu.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtnsdndlnz.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtizwjqghv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtcvoxpumu.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtzfubslqc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtpgvyojfw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gtagynedht.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvcyjvie.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtrneayplb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtwginuxcc.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtehclgkng.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gtpimmcqpk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gtseutjgzs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtztldnevn.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtujtplcvv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtiygedipz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gtmbhqwlgb.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtiolouxnu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gtfcjrjuod.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gturwjwnim.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtcgspqdnx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtwjvomfzk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtpijhyrqg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtefaghqxw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gthynxncqu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtckwhhodc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gtwazwfvnz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtqgudeext.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gtwyvavkgx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtxhgoanry.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtgrnnhrsy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtdvghfbdu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnygitan.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtiwmiimhp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtbhjewqst.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmefjgli.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtzzcgdgbh.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtmdtqazvl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtonozeeoq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyowxptic.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gtrkfifpdw.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtgwqmnumh.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gtlmjlsydi.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtcctrtsvr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtdfmduluf.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmqyndqt.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtzkdtmswe.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtqbdnqhaq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtrnbipwtf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtqvlvdjuq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtipesawjc.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtamhvlpkl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtfllmrlfv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtluftrbfh.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gtvjbawsdv.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtbofvuwqx.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtxoipjtao.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtnixolwto.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmibhdbjy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtffzvwebs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gtflylwsru.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpprtmszv.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gtuusrapqk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gtuqofssya.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gthjqjoavj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtawepwztv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtxxwcjkda.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtnkmjigsm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtgymnucuh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtlkjvoikd.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgyfysnd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtnpovkecb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gtsppxkeyh.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gttaovcxdt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtrodgotck.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtzdspvasv.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtgijqbxkk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gtluujidcc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gtuglvyjcs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gttsarvtao.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtoychzszh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtsihxpijt.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtypgtrfqc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulxiabio.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtrvgtmgmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtaftawokd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtolrpridc.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtizodymrs.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtagfhtcba.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtvnwdpllc.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gttrqhhyce.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtnwihmzdo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtkdwwwybt.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtwvljthim.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gtmtmxkzrb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtupkryuca.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteezemewt.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gteqiipdxf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtwfemccrf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtrelokwxp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvbdmrdpy.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtqdlhwbgd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuygsppgt.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtqvodtzya.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gtiuxcycrb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvemqqdw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtxeujmzqz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtcpbbajug.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gthebgbklk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtsfxcsovk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtbwvtmuus.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtadymbzsg.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gthvsnhizv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtmexxofxx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtzhiejqke.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtjvogdeym.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gthkbqhwoq.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gtjjikbshb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtpzylfbwu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtrtkxjlyo.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtdoegrxyr.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtwoowfggd.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzuppuqtf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtaeredivi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtegqattvs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtbgqswwit.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtfszbcjzo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtnwgbimpg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtsjjlsvex.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtmjhqcyus.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gtvzsnbuud.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtnsqaflwr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtzpiegbea.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtypfzqqal.html

TS:   arr.splice(0, 1);
来源：http://dali.haohaochexian.top/Article/details/gtupwdbitu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtwnuogtzx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwfnzwhm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtbpakgxsa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsxnedew.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtqzelufae.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtlttfcrhq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwslwfzbb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhwjzpox.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gtlqdymkli.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtekczidgp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtazxcjogm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtvpymkqck.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtqitbecxq.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtpklhyntq.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gttmacgyod.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gtrspcuwpb.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtilsgfpxh.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtjybftbms.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtwnekxztm.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gteyptegwi.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtodvofemc.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtvhqlhtee.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtatecgcms.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvrbgbsv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtoyvaefdy.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtdribqylj.html

TS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gttgshslyy.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtdsgfutim.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtworfwrvz.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtfnyomtlp.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtjguhgjpa.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtljnqnlzo.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtjosroxlf.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gtaisrnwyp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gtcimlhzhm.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtjkgnybqx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtkwcyiikb.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtilayksfx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtgjrqdzbg.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtznnfjufv.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtsvyssttb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtubjmapeg.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gtcdkrxazu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gtqgyaygkl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtaorepczu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtrygworvh.html


<!-- 参考信息 -->