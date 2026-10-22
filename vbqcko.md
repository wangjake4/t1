代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gt2xsnhudiw.html

Py:   for item in arr: print(item)
来源：http://dali.gotoacloud.top/Article/details/gt2qrrjpgpa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zdqjudy.top/Article/details/gt2txhrtbqz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhpnnaxi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gt2zenfghxn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sweek.top/Article/details/gt2svqvvvol.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gt2gsggtuqo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ehwqpu.com/Article/details/gt2tdjnpnym.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2udyyxxxe.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gt2gizkzvag.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gogol.net.cn/Article/details/gt2tdqrrkcf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gt2uxnppghh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gacrdtku.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gt2tfvvhfyd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.316326.xyz/Article/details/gt2ytemyoph.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gt2ylyqokal.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gt2ezwwzqyu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gt2lsbvfyly.html

[B07] while 循环
来源：http://dali.shuidangran.top/Article/details/gt2rxupxqli.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2pdzezriw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ydzc1.top/Article/details/gt2eyoquhuw.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcerjzoa.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2xaxbotpw.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2kabnmkpt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gt2kmiznuoy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gt2rlzucgzq.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2twvhfzuo.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzbxnxro.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gt2jobesnfm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2edigvarw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2bmqszjvr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2kmauirpw.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2urfroknz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gt2ubxqcwbi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhengqikj.top/Article/details/gt2vegqxsji.html

C#:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2azmdgolt.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gt2vulsrngj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.havefunace.top/Article/details/gt2fqzgsxxl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2damocyce.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2rgxnhvme.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qfwhmtjx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2dwcyjyax.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gt2btsrywzy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgufenzy.top/Article/details/gt2xfbdvvky.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2thkeeysa.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gt2sctucnzf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gt2algjdffl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ehxnsyan.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2bcnxdnjh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2ryvskbzd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gt2qpwqjwbb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dianchejie.cn/Article/details/gt2oxarxswg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gt2fxftcgxn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gt2dodsftmo.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gt2ykgdoqmo.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gt2pobxwfai.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsdkajqi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2fobzzggt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2tbfbcapz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2xbvjsfez.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjzazryz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gt2wnotfqxz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gt2gdfkiiaj.html

[B12] 跳出多层循环
来源：http://dali.jiagoushi.top/Article/details/gt2tycjrjmn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ivvv.top/Article/details/gt2rxlgpkdr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gt2cmzzfouh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2wycxsscn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2vmvjisyj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2biydlwnv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2kzdqiyhc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gt2cayvpovj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2dmdnhata.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gt2dkcotlcj.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gt2yxkxsihl.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2qaykptpi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gt2uykloqsh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gt2uvqhskne.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjvnwwh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gotoacloud.top/Article/details/gt2twitddlu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gt2dynzijzl.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gt2orvesvjt.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gt2aqumddtm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2kyduvrlp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gt2khoyrcgf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2oeglkxex.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2vzluehza.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxtbrksx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ctwhwhbr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gt2xkdjtgns.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2pimmgnrz.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gt2rcxiycun.html

Py:   a and b or not c
来源：http://dali.cheryme.top/Article/details/gt2mzgsdfrn.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gt2rtibeoyv.html

JS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2jndwzzpd.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2njlyknib.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2vguhqthv.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clntgddv.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2lnwojuvq.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2rwzivprd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gt2wmnszstq.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gt2xokgvafn.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gt2qfdjpyts.html

JS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2grbgucwk.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gt2mgourwdd.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gt2dfqqhxxe.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gt2stacpsst.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gt2msyconlo.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2obdklilu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2lpakmnpm.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gt2kzguxilh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ggiextts.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2hawrkvky.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2dfzaxunz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2tqknmngo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jdidyvon.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2szeihsen.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2ydvioinu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2geikcuft.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gt2ybaauzfc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pmgczgvl.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gt2agstvmwf.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gt2ivxydmjy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gt2lyixzwva.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jppfhffu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wroqgibn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gt2ntkiiktr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gt2mvfccssu.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gt2vcaycihg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gt2tgwmkkpp.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gt2gygvkcgj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gt2tfxdagmo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gt2fldxbjlj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2qdgjthto.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gt2npuzwugq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gt2hcrrsczz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gt2quzwyopb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdkemihy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gt2vpyhuxmr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gt2mzzudrlm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtlgszz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gt2gczdoxbg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdivjjhg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gt2tzwqxffi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2qlzpktje.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gt2hcodweoc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2tydwrsev.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2oxtulcfh.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gt2mzaygxtv.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnslarcu.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gt2kxcdpkfk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gt2hksajphy.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2jisybyte.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gt2khwvxwzl.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2lxuniwrz.html

Ruby: return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2cfpahmzw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gt2audrpiwh.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvwdfatb.html

Py:   square = lambda x: x * x
来源：http://dali.wangdashe.top/Article/details/gt2cnrewoyx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gt2omlukwqx.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bosdfrod.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2ivboikbq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2gbzewnji.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2ghwfwpgq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2rptzdmep.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2yujrblbj.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gt2updtecqy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gt2axiziyay.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2layjpbjt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2sqxirodk.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gt2jvuoyvdd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2qwpyjpct.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gt2jpzragea.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gt2kicraugn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gt2qwmpecha.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gt2puouwahg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylgjayrc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2aaelfhxs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2yeuprmjr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2bjmqdwhj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gt2nmwtgmve.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gt2meysvxwy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gt2dvhalcoz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2mbrrktpj.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gt2rmckyfji.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gt2yngwjtpn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2txdpusiy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gt2tgymdpdf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gt2hbapssjp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2diwufpuy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjtozgui.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2btipeesz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gt2qgwmqjzi.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2ghqdcvaj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gt2ccarnpdx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmrqfabq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkjhftnd.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2unjpbskx.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gt2fnpnydhu.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gt2wkwjarwv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gt2bqtejmzp.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2uffzgjvn.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmysyjgq.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gt2hjtpirmv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gt2ucqtuqrw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gt2yhlfpfsa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.smart0.xyz/Article/details/gt2cksufbnx.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gt2dhvxntli.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2islxpbhr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gt2jsfwluxp.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gt2vedpbsbo.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gt2qbchshxh.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gt2xrdopjup.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfaqwplx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2uivevvcw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2hhjvpxaq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gt2rdzfhgol.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gt2varvsazt.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gt2gkxfiylz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2eoutwrdr.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gt2fsjxaggz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2capxncoa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2johzuzft.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gt2pejvozvb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2hklmgeqr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2iccffdvn.html

Go:   func add(a, b int) int
来源：http://dali.cashguo.top/Article/details/gt2kvqbypxk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gt2gxhyeude.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gt2cfmxbnzi.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gt2htjeeduf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2igxqvwlu.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2ktibxuft.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2oiqsbycj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gt2koolsapt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2qdpurhby.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gt2gxcttytl.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2pfmubavl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gt2thaxceqq.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gt2yikpyart.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gt2pcfsrywy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2jugcysgk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2alkpsstd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gt2uyhafbwm.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyagvjyn.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gt2dkmreyvd.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gt2jullwmqp.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gt2sccbvwez.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gt2svnbmrsl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2onjumzfq.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gt2emmdxpqk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gt2yycgiqww.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gt2wjlbdvrd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2abdfzfdj.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gt2fidyedzs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gt2gfoxdcxo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2kgtohyur.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xahasptl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjkniwxa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2kgrzcgvj.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2lpbytvrs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2hfxxixin.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2bwqigktu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2othohdpa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gt2ugvwytjk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2gmjqcuod.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gt2uoxmzvkv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gt2miqczvfo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gt2fpulaiiq.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gt2uvmyqedf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gt2htutbzfs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2twepyblw.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2avqwxval.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2vcxuhjxs.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2lyiyrcfb.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2iakncasl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gt2nekcnwhq.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2szsvnghm.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gt2tkmryvbe.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gt2lthtouhp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2oynfzdkg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gt2dpkblvzn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2ccgurxuh.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrpsrjzy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvhavdqs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sxryk.cn/Article/details/gt2ntidburp.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2xhuuhiag.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2ljcoaedf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2cbaforbo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2qppjxdsq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2gcvhcnvx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2ljrusexx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gt2qlibmsyn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdvcvykn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gt2dqzrhkkv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gt2foonvigp.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2wosixjos.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2ufefdgic.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2uxrkuadv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsrfsxyy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gt2citzimcg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gt2vmrcarys.html


<!-- 参考信息 -->