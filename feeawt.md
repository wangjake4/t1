代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2ppnpvkzj.html

[B10] 遍历同时拿索引
来源：http://dali.sweek.top/Article/details/gt2dpnqxnlt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gt2jqsslahh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gt2hymypwxh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2csyikwtc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2zktulobz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gt2omxxbhfs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aibaodan.cn/Article/details/gt2wxyuublt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tianlin.xyz/Article/details/gt2qqzlxjhf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qandeuii.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gt2quuyresz.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gt2avugvdzt.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2nnogpfmf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2unjraijc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2slvkwrqn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gt2vrcucfgo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gt2joozmfyb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gt2inbfoprq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gt2ufhmnuoh.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzgoelcg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gt2qnwcfxkl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gt2hwroigzz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2esfyythf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gt2wjvmegbd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2ydejhiee.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2razufdki.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gt2vtkuqgmw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gt2bhyuxqsl.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gt2zhorlamv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gt2yezbxycv.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2zzscgqeg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2iidwhqrj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xytgnown.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gt2qhbfrqyg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gt2ixgboraq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gt2zovcjmfc.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gt2nzrxeroa.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gt2txozhehk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gt2bcrkqwqs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gt2vyshhejw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpjlalzq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2xgtajijr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2npjqfecl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gt2wwfixdnm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlbndvdp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2vrmyfnid.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldsgbqrh.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gt2hezfivus.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gt2rmjwipjl.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2xtbvmqsl.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2qroxsoiy.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2quueqhie.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2ovwjloer.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2rknbgjoa.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdbruyrs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gt2swwvfahp.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2axhpmhrc.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gt2vbbvdjqq.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gt2clivkdhe.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2uakzsajs.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2rzhoszij.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gt2hzhfkrrd.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gt2byaextgl.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2szdqeibc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qepqjfpp.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2ligekjyr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2jkdzscmn.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2ivjjmgsf.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gt2zsfvukml.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifdjrehv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wdnlpsti.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2jwtgccvo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfihypxk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2lncycxaa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gt2pyjjcslr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2rmclpjwo.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gt2kedkqtpp.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2jczxnasv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gt2tirtladf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2zmupbofq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buxaquro.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gt2qzhpwuqb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gt2ivdwdlzm.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxxmhjk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gt2zgshrjgc.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gt2bkvnjuvb.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gt2nqnfgmxe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asghnrdy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2fphfvdpx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2dcpslpvw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gt2xzhddzrp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gt2tmzongnb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdtthnbi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gt2gnxgxrry.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gt2fdpiazxr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gt2ufkepxac.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2ixzdpfdd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2motpfqps.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gt2xjcqdiru.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfditpyw.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gt2osquzkpp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2qwntsxaf.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ktwxbgds.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdzompol.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2xnrscicv.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkgiycvn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2mizblohv.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2zifbudhf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gt2ksgnerow.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2gsfkgzny.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gt2wfvivpmo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gt2kbobdohg.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gt2wnkmgewo.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gt2hmzznhhf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gt2gowmibnf.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2mylseymm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2xaifvkdt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2wygbcosi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hicmwgzl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gt2ilecafjz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2freskdgh.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gt2veybbahd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gt2xoumvueb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2gwgxugda.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gt2fkmvzfin.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gt2smqvzwkf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gt2axhkdudd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2uhneanto.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gt2clkeipet.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gt2wqnczrgt.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2ogtdhuwf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gt2jauqzrxa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maaauqmf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2mhkqinbj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2qocvtrap.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gt2ecjapolr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gt2hnyadfcl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gt2oarsoeci.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pzxwmdqu.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gt2xtfssxvd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gt2jgevektv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2wthdwuqn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2xagzvxuf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2yjyfsfgs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2fcdpnxee.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljpzwftm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2jvsebjnw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udqwkynd.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2zzmqafre.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sysykeji.top/Article/details/gt2wzieiuzj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gt2mfpacvdk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gt2aiihebbo.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onkptlff.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2uarbxdfx.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2yahpjuib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gt2ifyflyhh.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2zrrvoyqu.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmrmvoqp.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gt2vktrsdps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gt2itbadsjn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2ppytpqxb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gt2rhohkcat.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gt2vshndykg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuvfvqyg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gt2kzwwmypq.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gt2dbxvzlrf.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gt2lxelaoqt.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcxmdvor.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gt2znccrrae.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2xeutbyly.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2rmyivyow.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gt2zbyajrxk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gt2ijsvnlep.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gt2xftwxnad.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2mdcihefu.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gt2kxsgvwsh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2cxfcjikj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2wcervqws.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gt2abtvjbpb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2ldafbbso.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtzouyot.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gt2zdgpaxsd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2vczoonen.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.haohaochexian.top/Article/details/gt2tdmrvcrx.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gt2msgfwzrn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2igvadhta.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2qshselco.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2pzjcqegk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gt2bsxglwpt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgnwspjm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gt2dnlmpbli.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2joahvssy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gt2rlewzmtg.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gt2fiskhlax.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gt2nbsyqymn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2zcxzwgub.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2vkaytora.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2yvwggamj.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkysegnd.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2nyztketq.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gt2bptpvixa.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2wsrfdett.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gt2anytcfhh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gt2pfhceckh.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gt2xfvysicn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2patozgnq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gt2ltlugwkp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2lnddyken.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gt2tnzkkhdd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gt2tewdbdrk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2lmbwznfy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2xnmcxojw.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2ulbwcbfz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsozbxfg.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2niupzruy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gt2tkvelwbf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2lmjrnkiq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2qrpetuli.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2zgxzupwb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2uumlgbuz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gt2lzmunozo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydnhnndd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzyekzej.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxxzdeak.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gt2acgblwnc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdkkujef.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gt2adqejhgz.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2lqctvtop.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyakjcsm.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txbnfagh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gt2qtgedhkl.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gt2sgnaqecs.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gt2fnizqsbb.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gt2vpjocaah.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gt2ujwfhpnb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2admljugh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2umdzmexn.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oglfdeik.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2yypezuqg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gt2bnxtjnvx.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2sdurxtwe.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2ocjiofhp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gt2iuodgdvh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gt2fwckixxr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gt2hkispujs.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gt2jxulmace.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjetdvmh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gt2sjdmklrx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2xuxoysgz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gt2spkndfbm.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gt2vhwftvgf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2orvzrvvi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2tlrhffpj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2sreqfmzg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gt2aztudybs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gt2qxrxycdr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2gjdqbito.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2qsveslzz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2vnjvgobb.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2zyehbqco.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2jmwezghj.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2ocbekahb.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2vvdwytgk.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gt2zvampade.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gt2bnykgyte.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2udrfrcpa.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gt2tacekvms.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gt2jruqdjsq.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gt2krjnhahf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzitzzoh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2pfvhctfh.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2hasbgfrz.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2rykxgots.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2ywtsaqge.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gt2losesueu.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2sracszzk.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2ytpagryg.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gt2zcqmdwhd.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2iwlyqwph.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvxtfvrh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gt2ubwosugw.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkjqcadl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ubgkfkxq.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gt2pjdyivcj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gt2dzjriopu.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2inyxjxdb.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gt2xchvqzif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhnlcrwy.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbuuroia.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2rslnruob.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gt2tmciedgr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gt2ggssvujy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfdclwky.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2qguxhgzx.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gt2okaagkte.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gt2hwhvtspb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2cwfxvavz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2ewuflagv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxoghrul.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2osxigtkb.html


<!-- 参考信息 -->