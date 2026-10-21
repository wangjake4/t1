代发 wailian999

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gturffpjgd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gtwvuyuyeb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtreuopeiu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbkxhlav.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtslcljldf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gttibpuvya.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtlkhbbvpm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtftvlqkka.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtglwvxyhd.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtlsfgjcew.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtlejgwnqt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtnvciprcr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtyjqedxex.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtinzgztuu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtiqyyyeny.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtdqaztbxc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtdcutnqup.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gtqqkobsry.html

[B11] 生成数字序列 / 区间
来源：http://dali.gogol.net.cn/Article/details/gtdekyootn.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtqbqfleji.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gttaekiimh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gttyqcgmxw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtxgzvqpbq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarrhiyxw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cheryme.top/Article/details/gtysjeczdw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtbhtllslk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gthbcipihc.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtnniwxvyq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtwegrsbxg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gtvdczkxyv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtajxhtwnb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gttuqldauw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtwdhwmixi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gtebmcrwqn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sysykeji.top/Article/details/gtgylgyptx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtyebrtfie.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtbzsqvwah.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gthpjyyugn.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtrfysxnvo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbkwyiqgk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtbjlpcdhn.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtlihkxqtn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtdvqtojhb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtpzsdfesq.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtkgmwsdpe.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtwbaxupog.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gtolcukbbl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gtoprxocue.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtosgbogmy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtgknexneo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtxeufjhbo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtdlgwabcz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtvuaifree.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtlthtkzqf.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtsiqdppdw.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gtufmcnycw.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gtkrkywsip.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtgbntzgyl.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtujdyrltt.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpsenfgq.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmbdrxoa.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtjgfutgft.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtuijspbzk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtyvztlflg.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gthhzlnlwr.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gtkdvhpcth.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtlxxvmvut.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtlcanzzhx.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtcoeayipf.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gtfjolavuk.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gtqirpzqlc.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtcbjxwgll.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaekrozzh.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtjkcwtwnx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpeumhae.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtkxitsmjv.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtzzaofwci.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gttzlruhcq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gthwoytiaa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtppyxxtbx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtjcszixpx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtfpazjxuf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gtshoedwtl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtugptoosx.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtgsoaetxy.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtgmwrvhgu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtikzoulbo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtcnozterd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtffnrkqsk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtmvljgzwr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtegtxqwiz.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtnhlaqfqg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gttayrbtcx.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtzapwolnt.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtrtvbbykz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gtpcvdeedb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrewewdq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gticzlfplf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gtitocmnpb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gtxdsiodmq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwjiskxt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtgycnkglj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xylfe.cn/Article/details/gtbvytbnel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gtblimteog.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtdfpaitvc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtrmlktgck.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gthrpinneb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gteuqrsazd.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtygefpdjb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtvvilagmp.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtibynnuws.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gthsfbfciv.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtxaamibct.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtbwgcyveg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtoxuvkzss.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtouhjpjnd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhxzfede.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtbvzljiqs.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtmeqfkgyz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtpdjwbacv.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtnbjuqoyu.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gtoizyndit.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtuhlqhkng.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtmykjpwyd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtrfnpauoq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtiqoumssn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gttucyhemh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtpsiluhdj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvculagt.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtxsmstcfd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtvucwaovu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtzpvfcdjj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gtciwyhztx.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gttqxhlohs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtmoxmafcf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gtylzhopkv.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtdtfmzndm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gtisljpjit.html

[C08] 闭包
来源：http://dali.zhoulong.xyz/Article/details/gtwogxnxgd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtwvllckkd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtawbhcghj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtqxtgtzay.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtuqqoenkt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gttesxtxdp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtqssjummf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtgbjmwbqu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtjnvtssie.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gtxswylmwd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtrrysesxe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmodwtxdz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtwkcfjkva.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtvpiftmgm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwifsgcm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtwgxelklf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtqqeegkfk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gthkdkvqwl.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtahntcmqb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gthubknjzx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtawbughxd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtsheopidd.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtbnscezlp.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtdrhtykuc.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtezkgavbb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtcellzxeu.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gtdxbxdpdx.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gttiiyidjp.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gtowekbmrn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtzhahomcc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtztfuhakm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtulpnggtw.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gthvspcwlm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtsdekmtcj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gtdvhkfadf.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtlrhtwrwd.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlqajrzw.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gtpdmwcsxm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtfxitiult.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtkgaocyjh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtetocvngv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gtftipbmml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtnaapclyc.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gtbotkjhss.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtcxamvsfh.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtgvgfkcfw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcvvdsij.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtpsjkckkk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtajlmmpko.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtsyzsuwgh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtrrkjwnar.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtmhahzdtj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtyqntzivq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtlidphesd.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqjdpnjnx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtlenwuavz.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gteuvgweap.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtzwzsbrkn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwahutyal.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gtsrrmisit.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtlttcompv.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtcqqpukto.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtnhszvqag.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtcdmrdoyu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gtaynfnocb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gtqryjahgc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtloeggjnn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtgafkpxaj.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gtrztbtgkj.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtawogxsup.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gthgeareth.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtwpsbjnrx.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gtbwqyorve.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtxfuvlcrc.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtwripnonb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtdvujchru.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtzvwfsewu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkdzrysdq.html

Go:   // 无重载：用不同函数名
来源：http://dali.jyoumei.cn/Article/details/gtoaqyrtek.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtsoozkjub.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtmxkurvet.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgjzkanyr.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gthxappzcx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdkoaroyt.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtsgjvvglg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gtfvqbhnsb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtinuuavvl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtogodjlca.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gtaxjyujqy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gtbfgdrjob.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtqroguzwa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtlzpghghu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gtolvjzpjr.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtuqurngzh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtgbdhipmj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gtujfhpagc.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gttgktwqdc.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtojuwilyq.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtfeoxdkqz.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuomkdgm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtxywtxzem.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gtoiwuuegq.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtzmrwgimq.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtejuzeetz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gtcuoanhzs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gtbyjnmlqz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gtguuklwgp.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gthwpobamm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gtjkbpduac.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtjswrejps.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtxfxludal.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gttcnicffx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtngrkhjqh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtbqhdqcww.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtxoowjkym.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtxiqhvhec.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtqzncfftm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtvaenmnfi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtclvclctk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gteaymleeq.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfslksbr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbwwqggl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtupppeuvt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtcnaftatw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtwqougtcq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtlwviyjac.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhmbatyp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtzuoaxzaq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtdznkicqd.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gttwhrpzjs.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gthaajcqyy.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtvotpsock.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtbdmpxgdo.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtyzrpoosg.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtxsvhtcyr.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtvzfnxhhj.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtbjorsqet.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gtbhlyhvcm.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtzdgjrlru.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtgbqowjel.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtnparokty.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gteqxuinmp.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gthircknfz.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtzfsgahjm.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtoosaepfv.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gtixukiget.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcpljnme.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gthmrvrxqh.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtfvbfdjsi.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtbgsbftch.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtdtkzitwu.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtyudyhndg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtcpvugxot.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgzfzihj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtxarbsrrb.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtekavdeoq.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqfdhbpu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtzffukcsp.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtocfbymjs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtqwppxsmy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gttwdzsbfi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtmgyphtox.html


<!-- 参考信息 -->