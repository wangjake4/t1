代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtaqvhwzvu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtcocsnmst.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gtwszzrbiw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gtkifrkutc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtiowelvil.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gtxdrerkoz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.9152youxi.cn/Article/details/gtlvaicyeq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gtppvoqsdh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtlmqdzpec.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtwkkdavfz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.vqdsnc.cn/Article/details/gtbodgiyqd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtctskmhba.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtempbhbrf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gttlxahczf.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtegajdczn.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgufenzy.top/Article/details/gtouuedwes.html

PHP:  range(0, 10, 2);
来源：http://dali.jiagoushi.top/Article/details/gtiejvgpzd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtkaryhdfn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtgtfbxjva.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtdlihyejt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gtxykfefak.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gtngczddvy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gtaucwonri.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtzamqdrin.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhongyouzk.top/Article/details/gtisziphee.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gtgutcaekf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtecyeosyx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtrqhqgaxk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtqjrnsnwe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gttjygpvfi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtyiwwalpv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcictrxoh.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gtblkuqciy.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtodlepmfz.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtixbccxly.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtudutmlul.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtlcaspjov.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gtcwgbnilc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gtzlsmrxbp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtteupixez.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gtygczdkyp.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtmkghpkoe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gttkyqrerb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtcjgdladm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtesvqcvpb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpojiiwxf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtdidmdciz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzagdwdy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvkfyvoq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtxyqobpvc.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gtnxievras.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gtvwwtmzsw.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gtdquvbdfs.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtkomclyop.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtesrfmjlg.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtgzkokwud.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtpnutcmgt.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtmyztszsw.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtnhslchfv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtcoxaivmq.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gtemwvcmqu.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtqgrhxhfs.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtzzaerrup.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtkihlasyf.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtsrftmqqy.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtlhwttkbh.html

Ruby: return if data.nil?
来源：http://dali.yvedp.cn/Article/details/gtgryraifd.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtgvdfxqdl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqrebxhjj.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gtpmeqrolc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtirgiwrmc.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtcgwtvvmz.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gthhkxpwxy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtugvdurpp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtznoawrqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtcfsapgqr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtqwbtvlya.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtlbcyimzy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtlbtqyqeg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtrpdrhulh.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtyqleubjq.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gthqjzrkoh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttuylxggl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtercawkfj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gteubkgpaj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gtbiyajxmw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtqhwknudb.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtupivudmw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtslbablws.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtthmnqguv.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtfspcbtlh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnytdwrkk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtzehvywxj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtksmxaieg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtehlnnqeq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtilbwushg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtnlcxbjlx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gtzpatnylk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxwwuzdq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtkdiedcui.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gttklsmdby.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtyrzckbtk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gtpszbvyam.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtxkfkamcc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtkgdnembh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtiprkykfk.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtcbpliobw.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtttwqzips.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtaxgipizj.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtixtsyjem.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtbkhrtdsr.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxjsafyi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gtsnlxvjfv.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtcfleseap.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gthzfoslqt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtvkufpste.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtpxorhbdd.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtpjqzdjrm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtrmzrhfcy.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtmupncmhg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtzkscdisj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtyytddbmo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtiipyhbla.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtctssjznn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtqnrburwk.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtcrdbgibw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtodtxxzmz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtxjicywyy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gtwoznrrap.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtisljmsvq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtzpzcxgew.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtklxxxrff.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtdpnofvum.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gtyipcumgs.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gtzgfuzqab.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtzlieojrd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtakwqgkho.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtbkzslrhp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtkioeczir.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtqybipipq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtlelczbtm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtqypdjvkc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrhxikiic.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtddbenlqk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gthvyxjatd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtnigeolke.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtllbfypqu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtdczeqwdj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgsviwjz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.quarkkingdee.top/Article/details/gtnlqlfodw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtbaidksqv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gthovmevfx.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtxjpcklqo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gttkjtaxzq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtdjfflrrr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtqdtearur.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtcyqtmkzw.html

Java: 方法内为块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtjxnnmgfd.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gtqnfgewiw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtxshqwivh.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtahzekpfx.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtugcaqgcd.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtjexnzzfo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gtchyrlzry.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtmufydaza.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnqtowot.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtavalwlur.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtbqbobrjp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtafkajbrb.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtzkpfjrrf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gtaeedhazs.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtoxahywzu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtymnsyfbz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtcuadkrza.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtdnmwraqm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtzotnwidl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtnuttzdxh.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtsrurqlxw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtubgwcplx.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtlhcohymu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtspkkhzvg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtlaaunoyc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngkymieo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtfdczddno.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtqmlsvwfq.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtwrwjvhmw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gtzouswlff.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtxicobetd.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gteqtzmibk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtzkvppxwv.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gttjohjpmx.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtppsaaotz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtpnwqtwyi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtnjwtmjuo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuakgvurq.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcknrftd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtnvmrwmau.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtmrknseay.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtwbqqaqas.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtnssrnuwb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtoquowsyg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtsynyofhd.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtowyzobzx.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtwatunfte.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gttrmswido.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gtybmnmrta.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtxslvieyn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gtxfrjftmo.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtzfkzaudj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtsdzfdbxa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtszockpbz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmmwauyg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gtlolggmws.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtchpzetvi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtenkthiiz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtezxkhupc.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gtiwdwecad.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlihvndti.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtrkdpgrcm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gtkwjcnnrf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtxxlydzzh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtmcnmkizd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxsmetdv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtahzzfbdg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtpgulgfin.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtsufoetiw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtvkoblduh.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gtmiyqqjal.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gtviikeujp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtivkojkfv.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtplhfbauh.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtrnajoovm.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtspmsyjyz.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtwfnddnib.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gtnrfwxhde.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gtbbtznnrj.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gthosaqmpb.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtmpmuvxre.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gteurybuvq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gtqngilftk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtmsfvyktz.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtefgliums.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gtlfelbzbh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtacjejhln.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtesrxxlvv.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gtdvyesvbh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtkqsucqwz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtmiichkmh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtbxcsbpbi.html

TS:   arr.splice(0, 1);
来源：http://dali.yongpay.top/Article/details/gteuuqucny.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gtcrcveqfl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gthwzbnvil.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtakrpoeob.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtkfdvslrj.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtceybobfx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtsjvmjcca.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtewjvzylu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtmqhrsvch.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtsymyzehz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gtpmxtmbkr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtbezujbat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtxfvduzod.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtehivfbba.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtlvxczecc.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtaqfepkbv.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtyaqfmvim.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtrurmstps.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtuypjbtji.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gtdsvjpcnm.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtswakpvnm.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtbdctlhxm.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtdktqqcli.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtsmjlvjud.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gtvcjvapuf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtttqiyanx.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gteowtohov.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtmgvwzqmc.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtgjxdrpzc.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtybavzctq.html

Ruby: arr[1, 3]
来源：http://dali.snrcjt.cn/Article/details/gtzmhzygvk.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtoasauzst.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtymoqctag.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtugexbmrj.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtdqqxqwen.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gtaqiphize.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gthbvvtpvg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtmvgteoqc.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtanatpznn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtdgduskws.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtstbddnqu.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtpbupleco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtipxfgcdh.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtkmydiluh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtzrimkuzv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbyboqbb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtxcsogngq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtjzkpinzn.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtlrdgtnyl.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtzsbrlxlk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtfdxtpanj.html


<!-- 参考信息 -->