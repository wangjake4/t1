代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2rprnvppx.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gt2qtvifniq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gt2ljtqsvoq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gt2emgeotxa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gt2izltvdyl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gt2yodudsnr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258888.top/Article/details/gt2hmbneqiy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gt2pcmtzskf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gt2igjeevze.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gt2rbpcsqbf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrrbuoao.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmjidjsv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gt2avfxaqpc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzjbcaoo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gt2bobwtwnd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2liolxcsp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gt2clopilkf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2mjydsgih.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gt2oqgnkgoj.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gt2azsavfst.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qskqnyti.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2yuhaaxff.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2mxbcmqnm.html

Java: while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cxucdrpd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gt2zblcorip.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shuidangran.top/Article/details/gt2rwzyenla.html

C#:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2yycecamt.html

[B08] do-while（至少执行一次）
来源：http://dali.zhongyouzk.top/Article/details/gt2krfblftv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gt2qvecucaj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gt2xsmzdqoz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2rhdobaas.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2xtqgvdhb.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2bhmkgwts.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gt2yprjnmzh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gt2xlochbuk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjxqaiwe.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gt2texcyvsp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aibaodan.cn/Article/details/gt2kauoqynp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xxagubbi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2msdgjjde.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2qhyqxshp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cleycdim.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2vdtygcvv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gt2kuknxumj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2yyymwhds.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2wmrjkyef.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gt2khstcqbg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gt2zbybilrp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gt2hkpqwrij.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gt2awntngcd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gt2uomtbkyt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gt2bmybfhbp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gt2jwivffjn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2mqeldxqu.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gt2xkcepyfa.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2hlwekbuf.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gt2yjqqqmjv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2upmpbowb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gt2ohilbjfl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2rlhrokcm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gt2ottjehww.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gt2eirzrqlq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gt2alhtbvxq.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2hzbtavhr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gt2rxxljtkl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfastwvm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2verryjgz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2eltqhojt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2gbbwfbvc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ckcdysjo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gt2smhjbwya.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gt2ahhdpnsw.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxssrnig.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gt2egttqetk.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2vniokfmc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gt2cotztvys.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2wayxipcg.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gt2sbgmjskg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gt2bhpbkwez.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gzhubu.top/Article/details/gt2hiijagnq.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgrqrvil.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gt2xsjkqzva.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmripxur.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gt2jlnlhuil.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2qgulasaa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csuojoyc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyftxesr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2jdhdiyca.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdccrbbu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2koimrhdb.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gt2yebbrmfi.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gt2verjgrcg.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gt2qvenqxsd.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2gsssodqd.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2gzsxjrtb.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgessyki.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2peinngko.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2mzdeovuj.html

C#:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2jzakbwkr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gt2qhtgvlwm.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urkcvpmq.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gt2okmmvlgx.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2zmzrmegz.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2qyhxmunm.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gt2ryrsginp.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gt2opsbucfb.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gt2gctsuspo.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gt2tnbamhws.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wvemwlks.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gt2duqqcvrz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojqldxcd.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2qbawauoh.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2fuhbdiuv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vajhrcqh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2xpvufnnq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2upoypulh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nqhazyni.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gt2wssurtun.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okuksfav.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2ikpdqpqf.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gt2ipbsayja.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gt2pteimpca.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gt2dqoedztb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tdbtbutf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xzmjzfhj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2cjxxuqfh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrubumc.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gt2uksukavi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gt2rvbthbpb.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gt2wfnzevfi.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gt2vnpcphkw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2njaavchq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gt2vagtzehf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2licglzdi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gt2ezefgxnd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gt2xclfjucc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gt2nzvmtcub.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gt2fqwzpqro.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2fbpdbrlj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubslsuig.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgofflcb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2bpqmtwyt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhaumrbv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gt2ganolqhn.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gt2svfulamh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkwxptmf.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sycyxeje.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gt2gkkbllne.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2rwclulqt.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2sypkriww.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2gsoyhuyr.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2hmlocahz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gt2tydfljkr.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2kitnwmyq.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gt2pylbquuw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gt2trjmgwlu.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gt2hemcilly.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ksymxzbq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gt2vetlkfwu.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2bngdugya.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2phuvqvet.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gt2uhiytbiq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gt2qekqbuhs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gt2aurjbpbo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnjoxgqf.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqtxzexd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fengsongda.top/Article/details/gt2ukkgvncx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2uksiwbdn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gt2mgkyggiw.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gt2khartstz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2lmqszuet.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gt2cyxzrmmf.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2frntyedh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gt2qdbsbtfz.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gt2mwfuipdl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmvqgdli.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzufvwwe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaxlinyn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2ffsvisgo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gt2rlbwhyuu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gt2erhmeswy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gt2txtlffcr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2fxvdukve.html

[C09] 递归
来源：http://dali.yanxiufei.cn/Article/details/gt2bsqgksfu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2rgasbaec.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvdziaff.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2ewjfiyoi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2sdwevkuw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gt2ipjawbqi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gt2sdgmizdt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2opebasku.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gt2zzcrdrxp.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypzerenp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2rkbmqvyq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gt2hkmthjcj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gt2guejblgn.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2ghordlgz.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pztatwzk.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2mmdhtrlv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khfwuoww.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2pukjdtau.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gt2qerlpxka.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gt2omldixnc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gt2mfigpbzz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gt2tidslqrh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbjmigia.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gt2svaxhclj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmtyylka.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gt2rkrchtbf.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gt2kgbjwgww.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2ugjicwjk.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gt2ahpzddrd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gt2tgrvzanv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gt2cusnrqfo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfedaomc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gt2xqvuvvie.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gt2jnuwfjax.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gt2buvvoymb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gt2zalgbxqn.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gt2bcqtalmg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvrwcwry.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2jihyiqmn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqbpyniw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgvmapsk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2bjsnywde.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gt2bleymanu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gt2yamjflpa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gt2rqpbljpo.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gt2vgqhmaxb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkhztgwd.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2njzodeea.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2pyyridwo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gt2hiksoqxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gt2slhqywxa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gt2oyksakzk.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2vcjyegaj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gt2okhuzxbt.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gt2rzxedsaq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gt2lcwkjvha.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gt2ttdodnwy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2zwlqczst.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gt2bvxjwakq.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2wmkuygfg.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2lpwhsnqu.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gt2zorxbgzi.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2pjsyhrfh.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gt2qhjhfnip.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gt2mpcrdxwe.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gt2iikuomfs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gt2liahlxxh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gt2lqnojuli.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2thibalzx.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gt2wvntniim.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2zbowqfpk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2pkvvqxvh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2djaswmji.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gt2kuhxdrbv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ejwsiwah.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gt2ocxtwjhx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gt2kqrxkgxr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2dihwwnzv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gt2fipjtqux.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gt2menzplvp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gt2yihcnkna.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gt2xodkqvsc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2oerbqcrc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gt2lxfizcqm.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2uhweeqqd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2bssrwlbt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jefwwdew.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2gjbirdwh.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2vzbacixa.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gt2saomlsob.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2ezekqtxv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gt2qddichht.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2pzcrkxwp.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2tvvkxfls.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2kwhfjbrr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gt2ufdtewko.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gt2pljirldu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2pncxwxzv.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2sdeiucgw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gt2ugtodxab.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gt2hjqtqsmr.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2lmvzdchm.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctgquaoh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gt2tfnjuedm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gt2qkesnfrf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gt2seaphgvs.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gt2fbjizhid.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezzmomqp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gt2qviwvgqm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gt2mcwqgvvi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gt2eballdet.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gt2ejlzvaxi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2dpmkphih.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2jqxkgrzj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2omitjggd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2akaoiumg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gt2leimjxjz.html


<!-- 参考信息 -->