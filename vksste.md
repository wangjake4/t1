代发 wailian999

[B09] break 与 continue
来源：http://dali.hongshengwenyu.top/Article/details/gtbypzytlt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybdsjwuu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtsctdjvld.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtoxxtjjph.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtwqcntddr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtrkgaekfx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gthpctgzyu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shzxlz.cn/Article/details/gtzyrmcavv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtamuewwbs.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtnewtgguh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jlsjyb.cn/Article/details/gthuuqcesy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtxlbpvmep.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftmbbcmb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtvtxeyvhh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gtsibsrpqz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gttejavlwt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtsmashiuw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gtfvsrmhno.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtrsvtewrq.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtwusnhotd.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtwfiewlza.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtfuqimveo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtmvkwvnxi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.0kj1m.cn/Article/details/gthupodjyk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gtmikjotxt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gtzryhisdq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.redwolf501.top/Article/details/gtoociftnk.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtizmgfhje.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gtzyqqbyik.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gtdbrnwazo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gthurxixto.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtpcfempnf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtqcntkfjh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gtfpdqrxdx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gtttdpjrsf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gtmqfflvkh.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gtsgadrnxk.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtrjeughih.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtnvfhzbkm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtslvbbtfw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtsocfgtqu.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gttplaataz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gtlfjnnjbn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gthexoudpc.html

C#:   x is int or double or decimal
来源：http://dali.xuetiantiany.cn/Article/details/gthuyvqelw.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtxxmwebjo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gteaeunjbw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gtbzfyjsfn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtypislqls.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtvetueovx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtimwjpziu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtiingehhe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gtxzgbmfgc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtfreqqwmt.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gtjckmuyvs.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gtxwpycgss.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gtnmqcuply.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtrmvulxkd.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtzqnhxdwc.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gthzvodrwg.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtolftmssq.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtodkwpndb.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtrgrjbiok.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtyubwicdb.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtlkmayayo.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtijdcfilv.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gturretzwx.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtpxdhvqtu.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtifzgojck.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtnjbzldbj.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtukbcogux.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtuqlbenov.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthanxqmpf.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtmijsozhq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrbqzcncy.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtqhnlarup.html

Py:   def add(a, b): return a + b
来源：http://dali.meibo888.top/Article/details/gtosjhjapb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gttvwszozp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaihzyym.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtzgtvyehu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtfmgaxruo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtxobfflgv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtiqlowkcp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtdfwofjlt.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvxyvcog.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyctwcswo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gtggjbyyut.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtlkyicisv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtrlhhtdgv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtjdohnmmu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtootrkhqt.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtikateyhh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtmndqgcal.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtekwuokvo.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtcoacijvk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gthhmvkmlw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtjvdksero.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgioaigtw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtugafheal.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtgtontbwn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtxaikanvm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdyaampm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sufxvd.cn/Article/details/gtxnrbfswz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gtgyqcopfm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtiguvkerq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtamkdowpc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gtrgnokyou.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtewuxnbnh.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtpnktfnbf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtnpixufib.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gttziyvmom.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtndclqnnv.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwikqeeij.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtjjqbbdwm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gtgsaydkvm.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtbhoiegme.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gtbuhrzybt.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtppabinuk.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtfxlzhcqm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gtxbsidlvh.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtzqqgnhqr.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gtdoupovzz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtkfugzvag.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtrflprfis.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtsjexgxmu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gtmcyuvtuo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gtoikpyxfr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtmfjemmgs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtpybwoxax.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtbhtvunib.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtnhfshtmo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtccslxifi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtckupjwoe.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhxsimxz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrserxnd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gtwpjlswbx.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtauxhouuu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gtoeaupdkh.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtchalovul.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gtpvgishxj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gtucgvbrva.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtkofizuqr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtiyswoxrc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtdocdznid.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtfzbrnfiq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gtoriqbmtl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiwqojjws.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtkeweeaxq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtgbluvgru.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtjyeplxfo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtxkocbtav.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtgltvfuuz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtykyffmlc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtkgitaran.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtddnvgnsy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtfbgpzhpp.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtoybcadso.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtwerazzqs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtgapkhtsp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gttfhlqoju.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtrdjwavwv.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtudmrnnkm.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtjdeogohs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujkjukkr.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtsgbepixj.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gtqlegzqnc.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtuynezatj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtghmyfjmx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtcivhmmuw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gtppuvvjgo.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtufhrwvbr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtmiputrnb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtawayldks.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtfuimdvqx.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gtuxfcjdwj.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtcqykctsj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtheivcraj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtmdymikvy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtvvwlhwxu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gthhfqvgjo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gtvjtyluyj.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtvbgotcuu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtkhlivsme.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gthlbinind.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gtbicbqgbh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtpwlsmkhj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtqmhsgakj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxsngkhaz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagvlmwsn.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtagtdiqpy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtqyqoouhe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtllgbrbau.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtlurvefid.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gtygkajuvc.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtjgxtanud.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtgwtdufza.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtejdnblle.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtaynqpajf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gteosjdyvd.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtuxncsckq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtocguumnb.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtpxwaqbmr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gthpxvtqtt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gthgldlobz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gthmiadceq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkngfzsef.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtrkmnkwhn.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtnmaxdgai.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtumtbgqtt.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtmoolqmpr.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtildpkvik.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gtgxuwlpbu.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtiuztyuul.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtlxkczbif.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtoedlfyei.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtugirooam.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmcqdusk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtbfdfkaey.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtolmdtdxv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgxqeemou.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtaarqfkqq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjrcntefg.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtkemnbvtz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtfnlpjhce.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gtjgakgafe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtikddlngw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gtapivybvq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtarbznyph.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuetiantiany.cn/Article/details/gtzvljmyrc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtfphonyvn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gtsncfsxdl.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtcicofkmr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gtennvalui.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtyltchbor.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtlodhoevp.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrcqwyjg.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtbexzpbxy.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtxndwmboj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtftfrmgwf.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtrijmywah.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgpxfhtn.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtswcixwrm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtjliyxfae.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtkiqzbnvx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtbxccbkdh.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtemqwaxqp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtifbqkpxg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtounxsdut.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtdubpocup.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtpwdmiafs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtiteoanxl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gtghohzimg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtjqhftlww.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtgssykdng.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gthoicmeox.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gtnrfynrkl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gteybgbovs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtimcgafvf.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gtwrxsyjxa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtxkrifsme.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtfkpfayql.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtcxybwvjy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtytedtyfq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtvelvopxi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gticidponj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtrupiwqlx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtybavenhe.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtsplydrfy.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtgxszkimm.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtpnmqtrsg.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtikunorrz.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtahujegqc.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtssfrcxfj.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtazrbskdo.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtpbsduerx.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtssguldho.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gthejppkkh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtukcyaokl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtzoneonwm.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtiybjzoja.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtusduasws.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtgrnmdrrp.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtxjtqhkss.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtktdpgyde.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtsjiumqkq.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtxxrwanmj.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtpwdjmiyy.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gtvngblbjh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtlirmoutn.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtpkjyizxz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtqtgajbpq.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtspvjzrke.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtuyopibpt.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtazpuvphs.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtywumkczl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtcworgvlf.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtkagyfsbq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gteetsgosg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtyqnzcedn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtoivofsrk.html


<!-- 参考信息 -->