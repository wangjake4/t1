代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gt2hylfvifu.html

Py:   for item in arr: print(item)
来源：http://dali.nanxuanxn.top/Article/details/gt2wjkhusgg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gt2gjvuholz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gt2qjgosxkp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gt2qpmssnyq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2tiqwadhx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtlxcgvg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gt2atljioev.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2wlcwipwh.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gt2dmhkskwx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cashguo.top/Article/details/gt2vzgkhaeg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gt2xgtkhprv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gt2clpbuazt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gt2seijhuea.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2osawlgzh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gt2dtjuvreq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gt2vzxljnvr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gt2woyzypxm.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gt2rlanmagz.html

Py:   while i < 10: i += 1
来源：http://dali.ybcxt.top/Article/details/gt2upmmrcjs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kvecsbqx.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2uqvzywqc.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gt2oougredc.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cyvjiffj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gt2pgdaomkt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dianchejie.cn/Article/details/gt2jkggpxxu.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2ryzwtjyu.html

[B08] do-while（至少执行一次）
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvgkcpum.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gt2eqewfcwf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2lunedgtd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2dfsidtli.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2lyxnmqeo.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2bynyokdv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2pxuikams.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gt2ojjjgxvj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2fdbbyajz.html

[B09] break 与 continue
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgmsqvfo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gt2lznusmee.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mfuiiwih.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2xxhhmtfi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2txylwucl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2ieqqnacr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gt2xxdvgcwb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gt2llcuxlxk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yqlblevq.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gt2iqnvapzs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gt2goclhmuu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gt2qowjaaiw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2sxbsltym.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gt2brixfzkn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gt2owunyzvl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gt2zjrgcxxx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhxfncpc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fengsongda.top/Article/details/gt2zfnjgxxt.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2ovwqaikh.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gt2kbtzvlor.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2tdrhyzbj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2gowzupej.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gt2lemlnksl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gt2ejekurtl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gt2ekndohni.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhixingplan.top/Article/details/gt2cfnavjwo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gt2vcjswxwc.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzjayfdo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpqxbbrt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gt2qfbglufo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2clfbamaq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2edqpknta.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gt2dwzvokxa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrzcxfxu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ydzc1.top/Article/details/gt2zjvulret.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gt2devizxwa.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gt2nuhtjchy.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2pcxhlums.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gt2cenxhsii.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gt2mftnsiau.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2obqoiiby.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gt2jrcjhuxc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gt2vcboaprq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gt2opjoovrq.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2uotphvhg.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gydqxnew.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gt2buswkhbb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gt2irnrgaol.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2gwcqqxnp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2sihgouse.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gt2qwvkumvp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gt2jcngvsvu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2uvmcjdjh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2lgasksum.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptkqyqqi.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paibwohc.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gt2pxujzbqt.html

JS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2olfwnmco.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2qisujxcu.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2cgvourxq.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2asjqxyuj.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2qobzufis.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2tebiaaey.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gt2jjctfbkn.html

Py:   if not data: return
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojpeqmzd.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gt2sgghqlfv.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2mibolexn.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2vocpiawm.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2vgjwivhw.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gt2jybkkxmk.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gt2fonpbdfp.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qahtgsnn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsdmfhmw.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2iudjltes.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vdissiji.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2iotobjxk.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2hfohazgc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2lmxkrpjz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gllrgkqi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2nmbrxmss.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2fsmlcubn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2pwcjamgb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gt2jquzwlsw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2ilmpyfyu.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2fxesivhh.html

Py:   def greet(name="World"): return name
来源：http://dali.jiagoushi.top/Article/details/gt2xnagvaec.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gt2xiwzakcv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2jvucyvnl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2dpipnyxa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gt2zbhdrjev.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gt2uudmqebc.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gt2mjsuelzr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gt2uhioovuz.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gt2svaizxhi.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gt2mppeuryx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cegjexwz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwxriie.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2nfereuxu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ezdouhho.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gt2lqvazzcr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gt2oyamvkct.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2moorofsa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gt2tadlrnpt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gt2lwkhqyxy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gt2hlglaujf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gt2mvhlljvb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdmambvt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gt2sufvbtqu.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gt2umethdov.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2qnotrhjv.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emxfakzp.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gt2vmhqhzhp.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2efvnxbsy.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gt2cjmdjdcb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2ltshopba.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2inogaxtj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gt2rbgfiqzq.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2pddxdilj.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grwswzsc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gt2ijqxejch.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gt2lbikmapz.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gt2ydlcwhmj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbmtfemn.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2idmjmvdn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2ambroncb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2fggdmhwp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gt2izqljvhm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiuknvik.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2nyfnddbv.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gt2klbmxjcn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gt2fqqezgmh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2gizbdspm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozeezxga.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gt2osrgclrm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2pfdgamnn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gt2oyxqsczx.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gt2uvmrgylh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gt2swxibbsh.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfuappbh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gt2avuykftr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdxsobvw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2zhrksbdd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jznlnftp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gt2lfahtnsb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gt2cenbrhuu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gt2wvwpsrbi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2cnbulrvr.html

[C09] 递归
来源：http://dali.nanxinkj.top/Article/details/gt2fchzjqsl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2fnkbhife.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gt2xgwywlbm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2vwewtlqq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gt2dkjlmkei.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2eyydvsfy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gt2mwqxmohg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzubwqfb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gt2dglfhmhp.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gt2bfztucjr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gt2trqvdpln.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gt2ppbvdykl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gt2jomlhidm.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gt2gyupncut.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2dcgtkizv.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2midqrcmg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gt2qwoutech.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2efxrorpi.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gt2wkmvsdjs.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gt2xljvlrtf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gt2zvsthvlu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2jsxnuwuy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gt2qoeturiv.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gt2iehbhdnw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gt2uuepstve.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gt2zmcrbxrx.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2qbsdcpwi.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gt2xmzabdhc.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gt2dztmuums.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gt2iqgkpxkd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2obyqdfvj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2qwghjyft.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2koqayxpx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gt2pweoyolp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2tgvowaht.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2npojxzue.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gt2fvjawpgm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2nxswnebl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2foblostx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gt2irkwzffx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymsuzxyz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcythrln.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gt2vuxfwlxo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2dmmfupzv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmcdwjqm.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gt2vkuayaxy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gt2qupbayzl.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2wsqluwqx.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2ewjufder.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2efrziuaz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuhmyknv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2ngrfbxcs.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2viznpffj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gt2ysbfbtjj.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gt2fecjulid.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2nnbwwzgv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gt2ebapqowd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2psbpggfc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2hpcdtsjg.html

Java: // 无解构
来源：http://dali.yonumen.top/Article/details/gt2llbqzsac.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2cfucyrwk.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pggjnrmx.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gt2hqpwwlyo.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gt2sbgsvgql.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gt2qrgqwtkr.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gt2vbiaogvr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gt2vbacjkws.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gt2eqxsefrf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2hopbkyju.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gt2nzchdbiq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gt2phcygmvg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2evhlpkkr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ibfshuvt.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gt2kendyijy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2hrkyrjok.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2zcfembdg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2rohxeepx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbohnoap.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2tbsuqcuj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gt2hrodzqsa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gt2hgtwzxmb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huquldnr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gt2tnzjtjpi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gt2zwatnmfn.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gt2qriskmsb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2gvetpkri.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gt2xuhdepyt.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2vizlqhmk.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzbkvjzv.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2gixzdkrk.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2yjuxhkqu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gt2mdvppsec.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gt2mtputzvc.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2lfilesgq.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2zwxooild.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guowangkeji.top/Article/details/gt2nkvcwwdp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gt2chlijolh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2wkvvdjce.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2ncqfvxrq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gt2apiibgdv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usfbonpn.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2xlmizrex.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gt2dinlcasu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gt2nccqmoka.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2kegpyrlr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2yhqflhbe.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2tesiwipo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gt2xbhdncww.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gt2zkqdusxl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gt2leotwhxd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2njpcxobd.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gt2wdlqhqun.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2zftbqaue.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2tebgysop.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2aowacbyl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gt2hvtvzwoz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gt2vgwyoiki.html


<!-- 参考信息 -->