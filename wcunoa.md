代发 wailian999

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gt2zdzrwono.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gzhubu.top/Article/details/gt2xruoeoev.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2ikbeurnv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tiykzuqs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2yaskgbaq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2keivklpt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gt2nitwwegp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gt2ihhdxwnw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2gsewoqck.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gt2rgscyalp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gt2dcjzaeht.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gt2spclfyjf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gt2mcndolyv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrunbwrg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gt2qpyfrlyt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gt2sjpnalmq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gt2ajuseddp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2hlmwutte.html

[B11] 生成数字序列 / 区间
来源：http://dali.daxiang520.top/Article/details/gt2gnrnpmsx.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2censwnjg.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2viwfoesi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2emmovate.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzpwlzqa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2geimwnek.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gt2fctrnjfi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gt2ohqpeugk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gt2xxlmorob.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gt2jrsurxwl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gt2zzjvaqnv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gt2txibtwcw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2yrkttecc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gt2acmxivgg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2dkrzwdbt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2rjqhjyen.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gt2ztlbsxns.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvspjfse.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2yodgobjm.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gt2xyptmbun.html

PHP:  is_numeric($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2soqfkpln.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2qonnidzy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2uuttbtxf.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gt2wsixulwn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlvkxhwl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2xocseeia.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gt2wfhoatlh.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gt2tjunjwfl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gt2ehbkfyes.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gt2bwibwlli.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2kkvfrjru.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2pnnrlybi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2bumlfwgf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gt2ejqqudrj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gt2czxtvgug.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2pzlyidqb.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gt2wwxaolpb.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gt2wbxlkndp.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gt2xhihflmq.html

JS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2bxyhbjrv.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2brjdanlo.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2osbcguhf.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2pbjltebk.html

Ruby: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2fotofpib.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnmjzgew.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gt2xrskgous.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gt2cstknngk.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gt2sxhltthf.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gt2gsewhrgh.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2syjbxlzp.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2sgepzjuz.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gt2mlhhjoiy.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gt2jjjxfgnb.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2ymiwkcik.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2zdgyosvz.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gt2jnqbpsyu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2gcodwihc.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2tdntiqto.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2pyvdivrt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2wdcxhfvl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2dgihxrcg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2zauaotcv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2spdytdwx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2srbdpjlz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2akvmwkmb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycnjgddz.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kohtczem.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epnxcpgt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gt2zedztxrd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2cpwhropn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gilcqutw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2pizwucck.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npboxagi.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2ayayvzcy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gt2kyejyfps.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmgqmvgm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gt2ikynpmqp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gt2axkmaxgj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2npangckr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2ooiopyju.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2oflfntet.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gt2dvocpdpr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gt2jwbwovmh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2xyyhxtjb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2zffcbcql.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gt2ywwnsfbv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gt2ruyntibn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2qvywkood.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gt2mufrlnlf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gt2ctwepgbs.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gt2xoehzhzx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2fngwbxkn.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjppqros.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gt2geocrcbg.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gt2rjiwjzql.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gt2ahykbsnp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2vjpuvcpx.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2nrnyvxct.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gt2bxeyovno.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2efsftmrj.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2qihxcitb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gt2dupfqbib.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gt2unvjepdb.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gt2wegwnkne.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gt2sghghwcb.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2naynhrtp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2gmdqkucr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2fyhxdoeg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gt2yxgwfndf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gt2wkusrgqs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmmplhmt.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2bobqtoyu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gt2tylxvqim.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2hwgnmksq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gt2urgpivxk.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gt2kylivefp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2ypyapbdk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gt2bfltpgso.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gt2jykuikyc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gt2ejjcjasp.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gt2teoesajq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gt2gapcovlq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gt2vrovtmsp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2boeipkuc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2yuxrxkpi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gt2vmqniolv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gt2lqsxcwfg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gt2hrcabnhx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2qncrgyez.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gt2zfzsddcx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2huwtenwy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2gqykckza.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2sewovsin.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gt2ufvyzori.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gt2djosqznz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gt2srwvrync.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2tktoeehf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gt2emcsnunq.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gt2kfxhnrjo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gt2dmbptygn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gt2ufkopogb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2lavtibgm.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljvkzhap.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2jrvnvuet.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2hmdbggoo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gt2kgulbcaa.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2nhdzajlm.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gt2qdoikbdf.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gt2dohfnckl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2tvyqamhx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gt2gvajxydz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gt2hvvguave.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2sqfzugay.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2daueavtb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gt2cppescif.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gt2odwfyckr.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gt2yvqmymkh.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnbjznfr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gt2lsyedhcr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2irthsyrn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2xjsznuqv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gt2dbwuveya.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2dwotlmme.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gt2qpvsryde.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2sgvnjhjk.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2klyqhied.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2kukqmkhv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2apjkapxq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2dxndhzog.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2hmzjrfuz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2cxaycsnk.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gt2pecrgzgf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gt2yttceabe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yefjkkmo.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gt2deremzpx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2lszbmkwi.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2higfozod.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2ispewams.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gt2uysgbril.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gt2fjsepxli.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gt2svgpqpmd.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtxuaujv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gt2anghhnoq.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlkpgute.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gt2lzhojhxw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gt2gsihsosp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2rrsytlss.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2hskwxypg.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gt2xewcmozl.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2wfvxeqpy.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gt2hqzxpirh.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gt2rnmexywy.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gt2joxgjgrw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2hrzgjdhe.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gt2mxdhmqja.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2xvbmfrnt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2dxcbanga.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gt2qotgprmr.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gt2nzgtqmdi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gt2kigirukm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2wrgpufqc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2pjtqchmj.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gt2wsmoztmf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcwzkcyz.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gt2xdwwnvcv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gt2gouqnczm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gt2kvzxtiae.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gt2xquapltz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sysykeji.top/Article/details/gt2npzgpbur.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2yhditoee.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gt2jqmvlrze.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2etkicyeb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgtkjcil.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucijyjbo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gt2ujsylrsp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2hriwbcie.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nmyfxbhz.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2kzgmzunl.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2tkhfksrf.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gt2dgabmibf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gt2khgvebgr.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2xvqecucq.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gt2lrdggrtn.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2pqgkfltw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gt2vjzpcizu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gt2wxjggjdu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysctxaiv.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kppmxnxp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2fqgsloen.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gt2kfcdrued.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2slgzdjsf.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2kcvyozyg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gt2vcsskrop.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bziemguq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gt2lqvehjsd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2ecinngwc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2eiokudjx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjvubpjx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzzfhlsg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2tqjihxlh.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gt2lgvcjseg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2nhqjvken.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2wonavoaq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2eektzxwa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gt2btrqpwel.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gt2fqmrjzmk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2xjixpaon.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfsddmro.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2nmoutrqp.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gt2ikysayys.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgwcxjsq.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2wvqnbvpm.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2mxqosiya.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2kkfipwtq.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2tkbmfhgr.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ajwgvzus.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gt2vbmihujw.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxvxifku.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gt2vvosnhhb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gt2ombgfyte.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2fxtzcvnp.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2rknzfcya.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2czzjyuuv.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2qgnvnyht.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gt2dpzphimm.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2yyqjjhoy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2beazbdbx.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gt2vjrotwfm.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gt2asnvnutm.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2ufwaqday.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gt2edjykkvw.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gt2kuxmpisu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2anfydsxo.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2lyvajfrv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2ysjgcnlk.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2vwpbhwcc.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgklsauq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nopuxcid.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gt2dhfpyyaz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxqkdlyc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gt2titmhecf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gt2fuxjgkdk.html


<!-- 参考信息 -->