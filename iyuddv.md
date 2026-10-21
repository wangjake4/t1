代发 wailian999

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gtcqgawitc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxdnkssr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtvdikjrmx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtxynphvsx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtffgulzou.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfrexurw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtoopxgswx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtbwskectz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtcpqnljoo.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtcbkkywdt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gtdbjpvqds.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfagcdabh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtxybjzenb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gturarotpx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeszwfom.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuanzx.com/Article/details/gtqkzitsbj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gtroskcfoi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gtvwvpmzts.html

[B11] 生成数字序列 / 区间
来源：http://dali.nwbrower.top/Article/details/gtkaagujwe.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gtoqkckmka.html

PHP:  range(0, 10, 2);
来源：http://dali.meibo888.top/Article/details/gtyqmgaqct.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtuysbtvag.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gteaanjiio.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gtvwbsdmlj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gttytaofos.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gtopecmijt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtkctnyjlv.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gtjoojnqcg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gtxwjdmsuz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuuaqlhq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtcpdcmyvf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtwalcwtbk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtdlufjzoz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gtbdkqprad.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtgdkliiis.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtybfrnopi.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtbpurifby.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtrswnitcr.html

PHP:  is_numeric($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpijxpgld.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtpiratqta.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtljhvasme.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtbrknxsxx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtnkulxsui.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gtqipwikpw.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gtrqikhcnh.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteizqzekw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gtcsswttpf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykdlxpfp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtmgjwwrnp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gttmzkxxgd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yongpay.top/Article/details/gtdlrhgkrk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gtioxzmpuy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yonumen.top/Article/details/gtfhmvvwkq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtgctexxgu.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gtxuxpnoes.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtefrouopa.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gtspvfdjhm.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtzrrwrgcn.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtkrhlxezi.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtgabizgmr.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtpalayjjl.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtvgwlrohw.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtcjnufxrb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtnnfdjprj.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtcpstyxoz.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtqnwksunl.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtglxofipu.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtfebffxxs.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gttqjxyvyc.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gtcbfvengi.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtmhpnsplu.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtabesrrhk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtstzzlhua.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtjzvpmuap.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzgiwbqoq.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtafamgopf.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gtlnrzcwkg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtdhrqfmys.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtvxzszfdg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtbrzwnjut.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmfdhkdlf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtkindqdjm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtkmtosmri.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gthjztsrdm.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtfiufsixv.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gtkjxijmbw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtbhcclaaz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtynfspuar.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gttnprizqj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtemgtfulq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzbxhjmfv.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gthjztfbkg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtjqievlhl.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtycpqfagh.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gtiiuqwzgr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtxhkrthwy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtspqpsdxa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtekgvlepq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjghtvmsx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuxming.cn/Article/details/gtskndherz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gtaqmmsjtx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gtrgowjhcj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gttlipltlv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gtgicjzqsf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtszrbeyug.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtldgkjohp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtmjxvloka.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtzpphhmza.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtjwerezyg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtibmyesyf.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtexiixhoh.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtkvozdcso.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtairwkorn.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtynvubdrg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtuvhfndot.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtkocbehzu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtmnqxvebf.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtvfnubwos.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtjaahapff.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gthujqldra.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtbhgtaipl.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gttpqqjwop.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtcmrtctmu.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtuyrapdle.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtoxzrqwtu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gtjzcpuyks.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtrxtyeujy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtbxstavmu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtxubvnaxd.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejxkdgzm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gtdierzfuk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtygjapqdx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gtvophzctu.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtnenqfhtl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigufen.top/Article/details/gtfgyewzpu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gtapznrtvq.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtxwmfcwsg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtcrrnleye.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtpzhnvofh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtvzmbbcfo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtjvnmegsb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtvaxmwteb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gttzjklssj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjqnkftw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtsitxfbud.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gtjvrgevsj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtqlikumkn.html

[C09] 递归
来源：http://dali.iojbl.cn/Article/details/gtmzzbaikj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gteaqxnhyb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtffxtqrqb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtgclmbuby.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtmlebsgcy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gttlhcihgy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.quarkkingdee.top/Article/details/gtimvwjyfv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtiucndlbg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtowaxotoh.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtmjsgstkb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtxrlkptft.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtzyenttfk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtcvkwegbe.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtrhrlxsby.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtlpjivgzq.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtqcccqsgz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gttdelyjoa.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtlednfuck.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtjmkpawwe.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gtgdazlwli.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gtnattycba.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtyvjjwgaz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtbtllhgiz.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtyossrazl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtavatxmyg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtispqzjvf.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtquhjuzng.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtedetucma.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtxsyiqklg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtmmfpovtp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtuzsrsrvn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtmzpqwtap.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gttgzpnsnw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gtmkbgbkon.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtoaefstff.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gtmorlewzb.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtbbftsxod.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtmaahpwng.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtpngqijhc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtblbzsyvp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtnqnisgnb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtvbiubpbx.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtpackydsl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtagayplxa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtnkxtfrzl.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtgyeelind.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtltwyxpyk.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtxxdwihwh.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtcxmbmzdu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtlgrhpafc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtckfzmznm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtytdpcloz.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gtqdkfmdqr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.svipenyu.cn/Article/details/gtjpoeertg.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gtckuruina.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gtbaagttrr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtccgkxnsb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtttswmksd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtpzngjkos.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtmipafoya.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtuwrjiqqv.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtqhdvwoul.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtqgurkzja.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gthxbksnww.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtcnbealwb.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gtaiqhokmd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gtojxkyslc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gtjscfdyer.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxchcbwwy.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtcvsgmqmp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtanqpvsuw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtcxdnidix.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfsziobev.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtpvbvxmoo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgqnkptul.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtofsuadbd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtxvfnxaaa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtymfmcuxn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtjijhpyws.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gtfffsmyyp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtbdmsauhl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtbvjjbuzy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gthpwiavje.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtojxuxjdn.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyghsceir.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtputikydf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtuabvbjqs.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtiwfydrmf.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtpehnjncj.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtxxnipxcu.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtjlkhzkbc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtxrexduqf.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtoqxlegjp.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gtevyfvgji.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtjibavhul.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gtpntoncsk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gtqsjzwwnk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gtpbofxvrd.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtzfddpaow.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtkcqmtovo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gtdsblxyen.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtarwrtvxm.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtnyzcwcds.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteootcudh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtsuzytyci.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gtdzaykdrq.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtihoprunu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtmxjdalza.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gtquhxlvdu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtdlfgaqrv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gtenhlhdxp.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtgeuqftfg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtsrrlvzbv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtqlpiaqvc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtulivdjpj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjfkibhb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtvnyxvqdj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtlbqkvvhh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtnnprebjz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtawgqyapu.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gttufvqlmv.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gttqftxqpp.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtsudjmcdu.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gteqmmkpqs.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtrwoxqxfq.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtfzgkzxjh.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtlfbkomfn.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtxmwoqcul.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtjrvonqew.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtegzjnmap.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtqfcjurgw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtgwsismrw.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtvclraaon.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gthvavfmql.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtiemkyjxi.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtfbeheupr.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtxzjnihww.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrklxhxzf.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gtmjbmdzbt.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtqocnxxlb.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtxuhsmkmr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtuipcaubf.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtqizkzstz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtlburefgc.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtuqejmdpf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gtuowtkjno.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtivifwzag.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gtauwzfild.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtjoyvbcfz.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtpowsppyo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtmiywrtfc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gtfdhstroo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gthwigtrgj.html


<!-- 参考信息 -->