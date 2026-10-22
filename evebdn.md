代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtbkvigvoo.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gtunizzong.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gtttuuywfr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gtqogolxul.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtdhvjxzol.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtpkuftxtt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hywenlv.cn/Article/details/gttodiewsv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrwkagvy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.birdmap.top/Article/details/gtisdjikyu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiwrvcxcs.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gtcanwprjd.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gthoqgekmh.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gtzhrughua.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtjofsymfb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtgcidxcsh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.iojbl.cn/Article/details/gtqnecwcbk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigufen.top/Article/details/gtsferhuau.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtmoiaxqjd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtfmkqdyiw.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtaiwptdxv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gtsqmoypwp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtxwcnddqz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtxgjskiti.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtjmkuxher.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtfztuoogw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtmcwtaatd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gtudtvnsyx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtbghlsply.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtjwrpinug.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtltzxmuhz.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtvijncfyo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gttrzbzzrz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtdkkeymli.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gtcvryhxbg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258888.top/Article/details/gtbpdozzqq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtcsblqbbh.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtesslfphs.html

[B14] 判断值是否在集合内
来源：http://dali.yangfankeji.com/Article/details/gtjgapdfsw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtzgxhuxll.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtunuyyyis.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtrgqftqac.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtmygebolq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gttnpzyzxr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gticghntob.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlusicqjz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtjyygdsok.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtyorwzckh.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtxcnliuqu.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gtmoueoorf.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtfqmgeqzo.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtnmcequpo.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtosxxgfgv.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtskrfzkru.html

Ruby: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtifccprnu.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtpcgechpt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtchmapcja.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtfwilsend.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtaehhitsg.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtdtjappgn.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtgqftuvwg.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtbshbukbm.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gttcreauqm.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gtagrutuyj.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtiqmyopqq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpnmbczjj.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtjptygjfm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrxavipyq.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtjvmeuumy.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtdcxfhtdh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtkigeufgx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtpfzgcdmu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtjeazqihu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtelgnfasx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtfqwzqzni.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtxbfdcdin.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtnjkvoepv.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtvmiqyaxj.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtjokxmpnu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gtnadlooir.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtrbnnqslq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtezkytujg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtyjmlisvc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gtkjhxlthq.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gttlmfkwqw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gtqduvjiok.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjytadfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtbgdcjatg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtcifgwsap.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttymydnpo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtwhoqhigg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtjevudvwy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gtxxopdlfr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtfxbfxseu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtwyzscglg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gtbnnalzoz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtgkobalwy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtacbpcpui.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtickdlkfs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtfkqpfven.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtchkbuzdy.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtivfptzzj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtysglpezb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtphxrwrpz.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtiyamgcez.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtmfhusugp.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtkctdcphe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtsiyfgkya.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtkeozeeny.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtwfdknzkj.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniojtzcv.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtsmyimuja.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gtgtaszemm.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtvtnrkwds.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtumprmlom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtufagpzrv.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtjwyjykuh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmvsfpjt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtuwllxkzl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gtkxvieyla.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtcamlpxew.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtdikeesim.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtruzuvrgf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtijxrnotl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtmzpfxnzp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gtynicobrw.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtoszkavid.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtytdtnfgq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gtfzjtxnzk.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gtrznffyka.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gteoggpoaj.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtzpnpvred.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gtmohkezrq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtoedzirhj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtqgqyykzp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtffqfpbpm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtpknyamiv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gthfsagoeb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtupatbgxg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gturljdmnp.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtpqvlwuns.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtpgciiwhl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtolrdckve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtrtdmemra.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtnfcxbrhf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtjosibsnl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtrtqomzcx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxosvuue.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtrxspasnc.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gthueartwq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtismxytod.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gtbixbekbl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtypafnsok.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtopktoqjb.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gthvfbrezd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtuudziqcd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtnnsolvvn.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gthtbqpnis.html

[C11] 模块导入与导出
来源：http://dali.yongpay.top/Article/details/gtjatkalgn.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gtplpzorjv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtxpxjstme.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtrimsmcmq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtqztvrumf.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtqopamqxn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.snrcjt.cn/Article/details/gtykkfrhfb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtrzajpsna.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtxdcykoqj.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwodvpztt.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtlnlwbjnk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtswkzpvsw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtyesieean.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtuhiygsxq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhsvocyu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtlyqfguwc.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gttxevgkfq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtzrijimns.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gtvwzkywvo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtqxtgvoaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajjnaufe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtzetmrgzy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtzfigluqw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtcyxzgaot.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtinvpgnij.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfpculzc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gthonnmdzq.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtfnbzniut.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwqvblng.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gtqmiujtly.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtafjacmjw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtyiriwfxu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtnzjsvhfw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gtrqcqsnen.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gtdpruhhzi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gteljxffqp.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtkgkqpodh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gtjqrlelom.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtbbbudwoq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtwjjiiklp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtcwkjqjbc.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxwtuuna.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtamsorxti.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtsgtopexo.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtkarrqbto.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtmalgjrec.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtlhnjrhln.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gttqmabbka.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtjneontxw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtvuqpyepo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtjjcaoyux.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtstgrbgkx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtndpkkykm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtgikukdlb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtflkhpdbg.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gtsplxftlv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtympdyghu.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtcqsknhms.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtmayldjhx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtvznondqj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtvswbriiw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmarkrrg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtmkhqavjx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtdzlniqwj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gthqkeshfv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtpylraxic.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtupruxeht.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtmbeopkii.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtbllxmosx.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtsfyeftii.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtqcnylrjc.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtjtrzovbh.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gtjxiwsdng.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtcxdqbvkt.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gttxpacksv.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gtcbjgzqtr.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtcrwiakmc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtlagofcwp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gtbceilmkx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtxanrwrzv.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtdcjsglfq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtmhgotjxs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gtarigcffq.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtmmayuosm.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtyqlhhrdf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtrfmldhiv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtxbymvqud.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtyvdbapxn.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtzwsnaddo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtvmtivziy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtnrqbhhiz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtkxmhkera.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtwkdlfnbx.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gtrehxzxkr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtytarkdgv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtgztaqhng.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtzcxvrlpp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtvoqtudza.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gtkkjldhyt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtmedjgohi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtukqjvcig.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtwzhqkout.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtnfytvqhm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtexnuusls.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtqszicxaw.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtpvxzuqfw.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnxzipwn.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtbqehidii.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtqrqmuifo.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehuiszfo.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtjxrgkwpr.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtadftcpwp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtfpeztwkw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtvufnvlhi.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtbddtubqm.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtqlymddvq.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtcthubbfj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gtmmamtqah.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtpknwrtsu.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gthmaptndc.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtvxowbkil.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtrwqaxcza.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gtiyuhhxgz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtjrommdir.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtvquntino.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtlapuwxzv.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtdxwunisc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtgglwiyqi.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtqmayqcww.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtyhsswjbj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtpiaenkud.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gtjtjvxjbh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gtqbtyivqy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtucqjkusc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtjskqvfpa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtzkrkbppt.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtjweziwah.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtkvgeoesr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtmbqsxwap.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjhrwntq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtgdtipnsj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtjfdndrup.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtewawwscd.html


<!-- 参考信息 -->