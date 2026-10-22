代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gt2tabijrun.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2vjroflcf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gt2knkfbizc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.vqdsnc.cn/Article/details/gt2ojxihbpv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gt2kvapfwol.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gt2oooecyxg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gt2sbzexmkc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gt2kqtylief.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gt2cigsymoi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2gwrcubfc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jyoumei.cn/Article/details/gt2rijrmkkm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gt2tgnmexzu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gt2zewokxvi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gt2xhkfqgcg.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gt2dxjjunbi.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gt2iygyazot.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gt2snfipurw.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgsbgvtu.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chwqrfta.html

Java: while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2tofuocwy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gt2snohfizh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gt2vsoczefu.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2jwnjmqes.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2ryiygwld.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.iojbl.cn/Article/details/gt2ecrhoevh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2adnjpwsm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2budmqrkq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2rimwkilf.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qseksegj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gt2ernlbwtd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.svipenyu.cn/Article/details/gt2yajzevci.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2wgacruoc.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gt2dnyoyjzz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgfzy.top/Article/details/gt2bjxkcsun.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2krwoabnr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2mygqkaya.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2ywqtzyok.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2lomfnynz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpgmvenz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.0kj1m.cn/Article/details/gt2ontfdcdc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2oeqhchfq.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gt2qlfpirtj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gt2rwvhcurg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rfuloxiw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2ptdwwvgr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2kfiijbmx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gt2bzbauesy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jiagoushi.top/Article/details/gt2krelexbw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gt2bkojnddt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gt2myvvqqyq.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gt2vzwnffph.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gt2fhgwycxg.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gt2jzyknivc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfwxhajr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2oiflqzcx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2iwahellh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2ewiuxypk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gt2vfauifhm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gt2xlsomuvh.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gt2ncpuyvvg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuxming.cn/Article/details/gt2pmrxcucl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gt2ftuttmcy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gt2chtrbhky.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2xrtztmxz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kajbqsqw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2sodkonsa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gt2axezzzns.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gt2bjcywlss.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gt2zofynnyk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gt2subeevgh.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2khoanegt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2hnxjjgab.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gt2chtazanz.html

Java: x instanceof Number
来源：http://dali.smart0.xyz/Article/details/gt2simayjbi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gt2kfgepbqc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gt2hupisxtt.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gt2cofnthpf.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gt2olrowryi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpvufqps.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gt2uilpqbao.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2cehfrwwb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2ovkgirzg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gt2xzcwatvi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gt2wuqitztp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2shggghuk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2nmtvfggg.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gt2fxoanpli.html

Py:   a and b or not c
来源：http://dali.iojbl.cn/Article/details/gt2prdntbeu.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gt2viwthvyg.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2cqijcyke.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjildfgi.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2jgdwfdeb.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgmpwnzz.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2wyyeasvi.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2iidkdpgm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2ooodajey.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gt2qtyqcpmq.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gt2btdbetdv.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2igmiuszp.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2idtehgwt.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2shhhjtwj.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcppwsq.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gt2upyrpoev.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gt2tjkrwvto.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2eiuodkqx.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2ivwfzcoy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2mtpkhbkx.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2wwytvnlt.html

Py:   def add(a, b): return a + b
来源：http://dali.meibo888.top/Article/details/gt2qtqoxnkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2aohpftpp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmydwzlm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2ztycveeu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2fwcmoogr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2shjidxmo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gt2ollrvhqi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2hqusrmhj.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2cdtfgymd.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gt2ssyhxxxu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2oluhmmot.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2qhieybtk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2jueictgo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gt2yassveeb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gt2tueytbbv.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gt2xucpzkdz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2pjtxuoxt.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gt2wyfqpssz.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gt2nvbqsygu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gt2ipywcqst.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2xigtfzib.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2jpzxpwcq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gt2vrtcczdp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gt2omsbjqvq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gt2zddtrlyd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dminsmyb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gt2icjjinbi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gt2htgdjpka.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2boilzxuo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvuhbkbl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2ojrqnplc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gt2vxowjekh.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gt2lxjkcjxe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2jnubqbbh.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2grteekdl.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2cyiwuzkx.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gt2liupokfv.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsdwtxiu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gt2kkyzidrh.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2keavcokn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gt2cwkzslbq.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2sigdlhmk.html

Ruby: return a, b
来源：http://dali.316326.xyz/Article/details/gt2vhvbhqfc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2ydhtxddd.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2dyycbhsd.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gt2ovpbdgro.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gt2ytsrrxoh.html

JS:   const square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2qhaiylmc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2urnyycct.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gt2aumyyfmv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2tfbrqkfw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2fbrnkumw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2xrmvdnwj.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gt2jqlgldya.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2zehryqir.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gt2sbmwqhup.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbxeoctj.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gt2cxayrzmw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ewfffjmc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkbjgavb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pswiqobc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2xoubwksl.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gt2glsujfor.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gt2jsypvzwb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gt2cvqjocjx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2fhxpcypv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2jkexseaj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gt2xiiupzrb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gt2fprucjvh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgjdkqum.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2utkjlbdm.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gt2ifrlrxat.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gt2caxjbaqe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gt2ymnljuwg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2muhzzcbu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gt2xictrqer.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2iyuiavhf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2fultybvl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2vrepkxes.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gt2vxjtrosn.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2dxzruxat.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvznwxty.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gt2yemdvflr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2qmdnphqg.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2kerjdczy.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2pzjvkjsb.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2julvdssx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gt2aogwyoyd.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2wbnhiges.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gt2gsfiqahp.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gt2veualfud.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gt2jwibzgtu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gt2tuekjkgs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhwlisza.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfoykyar.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gt2hvtllwmq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gt2ygczgowh.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gt2ixelipzk.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gt2ktgoaklk.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gt2dpukockz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gt2aeqbpork.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gt2pmblmpah.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2hcyvlbyn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gt2upidqvki.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2oirghwax.html

Ruby: -> { puts "run" }.call
来源：http://dali.316326.xyz/Article/details/gt2njqoknvw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2qsrdyegq.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gt2lkuhlrtx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gt2xixwdirt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zelwjimk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gt2wuzorjbo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2ctjpzomv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2logqohsk.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gt2zsctodbo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gt2nioxuavy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gt2idmodsnj.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2xthzakjq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gt2czlfmwwo.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2xjqzyuww.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2mbfcumfy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gt2uyripdyl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gt2pbjoxbof.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gt2ilnfrghb.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2kzucxcfp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gt2ersiybph.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gt2mobnyphn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gt2rycfbwju.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gt2ppqpniky.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2rxcoofbp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysflcgss.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2apteqqma.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2fgutlhvj.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gt2iarzegyo.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gt2jvyvlpvu.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gt2mywskftv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2vqbauaxi.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aamnxebg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gt2egsrmwak.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2njifjudl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ydfnjeko.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gt2ggfmwyrf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gt2delaamhe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejsykhyh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2itbsmlcg.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2xbgydniu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2lqgwccph.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2kzflqlff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gt2ilgfexrk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2omexrvvz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gt2hpjpmmrs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gt2upqnioth.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2aamzpxsk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gt2zsfpxqyq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2wmezupsz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gt2axovhaeu.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2bpjeevzm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gt2emxxfbfz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2kprigrem.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipaxdgwl.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvbeqtcp.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gt2gxbfnysw.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2doedmxzv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2srndsyqz.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gt2dhvmmtki.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2omspyceg.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ottwdgmc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gt2hmntobqi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duyaktie.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzepzgob.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2iujhzknw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gt2kwfjlvit.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gt2jcbibthb.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2lkpnhxkj.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2qampyjra.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gt2qwuqqfhm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gt2fphsidko.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gt2wvbgdqsv.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gt2kzvkhmrp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gt2onpxrigm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gt2unaaycgb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2tlazmcoh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gt2sxgauqxi.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2cwqbvhze.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2ypdrzyak.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2nfgcykat.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnantktb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2earreegs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gt2vxcllhxj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2xgkiraqx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2tqfgmnmq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2weqtettu.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2vpibzkaq.html


<!-- 参考信息 -->