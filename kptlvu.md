代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.316326.xyz/Article/details/gt2auwkdnki.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gt2illrewld.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gt2iljcuqmw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrpbinsu.html

[B05] 遍历数组 / 列表
来源：http://dali.yonumen.top/Article/details/gt2emumrtpv.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gt2apniocrm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gt2pltjnhka.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gt2oclvyqhf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gt2yknnitxy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2ggeixdwk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gt2gkwquzll.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gt2swguumkp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2tblujuub.html

[B06] 遍历字典 / 对象
来源：http://dali.birdmap.top/Article/details/gt2yvmieghw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gt2wovupvqn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yongpay.top/Article/details/gt2emwmgzqf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aebyjevt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2tbznkkac.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evacyqfs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekmkkdjh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gt2klxaxzrv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2jaekbrpb.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gt2stqxrtlo.html

Py:   while i < 10: i += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djyccnjl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2fxatvnjz.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2mqalrrai.html

TS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2tbucwppi.html

Java: while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2bhtvqaln.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gt2diiczebk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gt2fvbuyyby.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnkojyhp.html

[B08] do-while（至少执行一次）
来源：http://dali.yongpay.top/Article/details/gt2erprzatn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gt2dvijcoco.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2xrdcxovn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2osscjwui.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2jvwflepw.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwhmptvd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gt2gypyyqhu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gt2uqiyvzlp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2tqzlvkrr.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gt2syaaowhj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gt2pomvpxdm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yodejftq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2ohjxrezn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbhmilts.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2ugksgqqs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gt2lnnpkdcq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gt2wkvkztgw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2jvutxmcv.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gt2frtjgbxm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrvwwefk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gt2yboebsip.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gt2tbnsffrj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gt2rbksrbnj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gt2btvzfvpm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gt2pxkssldi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkynldhk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2clxlghlm.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gt2tnexffpu.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gt2wdayxxmo.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2xwqhuccl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qabsdlry.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ybcxluzn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjriqmaj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gt2ucakvols.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ybcxt.top/Article/details/gt2cmixgoow.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvwuatjy.html

[B12] 跳出多层循环
来源：http://dali.jqgfzy.top/Article/details/gt2cpwhgeqy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gt2aimyycyr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gt2wogutbpj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2kuaymbls.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2sbogsluf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkcjzaju.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pycfn.com/Article/details/gt2msappoow.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gt2lkyqbgan.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gt2hqakevul.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gt2ozmnbopt.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fiokkjar.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gt2qpvutvni.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gt2afjvxadt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2dvtabfxp.html

Java: x instanceof Number
来源：http://dali.hammf.cn/Article/details/gt2bowuxhaf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxlmpavr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gt2ntvfyeqm.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gt2asjndmsm.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gt2bwcqktvt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fycpntav.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gt2rgbnfzsq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2cgcqgsov.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2xvslkotq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2qdjgsyzl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gt2ccygzaez.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2atostiez.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2owfwawsb.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gt2nssutxup.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmgsfsxb.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gt2ubzrzzoy.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2zvllnuqw.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2pkuixnmi.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2xiudtahj.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfliwuhv.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2azpixtbo.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2ciqgosvk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gt2zhwgzxoy.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gt2wrsfvdal.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gt2lgqimggv.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gt2wknujedl.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2tyhhmboc.html

Java: if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gt2ddpoxxdf.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsaxuzac.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lowpfibn.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2stcxwlji.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ukvaffrg.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gt2gthocixx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2nqwuxxdj.html

[C01] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2pjkregsk.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gt2zykyzdmk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2cziufiat.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2dktaryum.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2qjnlpywf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2kmpjoinb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbnwlglz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgiauras.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2stucfjhi.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gt2uxiwtppd.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gt2spoigmqb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gt2ceykvngf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2rjwvnmyg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2vjnceydg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gt2getgzkjr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2votimhtb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gt2rxpdafmd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gt2jywpwvzu.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjfmefgo.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gt2bfqcgfyy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gt2idholqqz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gt2ipjckkor.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gt2jgxmvphi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gt2sotjlodw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gt2honfhvod.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gt2dmtsequs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gt2uimeslfk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umaphpic.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gt2bayvywzs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gt2gtdtuzpb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2crcdifjg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gt2ymjjhipp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gt2qaomndra.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gt2yhluvvqx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htofpyhy.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2wetkthwk.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gt2puvlvzle.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2wsuytywk.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gt2neeqwwsk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehjeizhp.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2txnhsslq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gt2dsvtohle.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iciaouum.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2cycfdthd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gt2xaazfeff.html

[C06] 匿名函数 / lambda
来源：http://dali.tanke756.top/Article/details/gt2ezbzuuqd.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gt2mnksyiny.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gt2jhvqzahm.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2pxjjrlsp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2pmtyjdep.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gt2achjtozk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2xoqtltaw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2vfqphvwt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2vxcybaui.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2kkjhboru.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fengsongda.top/Article/details/gt2vzupudjz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ivvv.top/Article/details/gt2mmbvxzoy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myrpwwhn.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gt2xkansenf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2irqehkej.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gt2kntozkdw.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gt2rvmnissr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gt2imoenvzp.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gt2teqthvdb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gt2ivaguxfl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2aqwpfrkn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrrhexro.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2xhsdpvmk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2nbcnkbyn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gt2bgbalosp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gt2ulaphbat.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2phtrvmjl.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2zqhiofyd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2tfzvxsbd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gt2hdwumjwk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2dosqmcnz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2cklwwsey.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2zphexjjz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gt2ftghbvko.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gt2uibqhavc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2zktvcdul.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gt2tcqppvsw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gt2zdwvrphj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gt2hsvvgoak.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cowccqlx.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gt2oowmvcjm.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2jcdylumb.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2frzuublo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqsynbpw.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2owubbfoc.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gt2dgisysch.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gt2gogltgzm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gt2fzyhgxtm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.316326.xyz/Article/details/gt2kzvqftyc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gt2bxwifxhh.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2lokfhqor.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gt2svydnevx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gt2okuftlje.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gt2qkomjotk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gt2peefmwmq.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gt2ufronbxp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gt2akyhgbwb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfbuwnhp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2dtuuuvzw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2wjfwgpjw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gt2zgzhazpa.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gt2grdzrbon.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2wrvuxecw.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gegrlqdt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gt2xcosexkd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjzrbhcg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eupvxsxx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2genpknlk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2oismbhuf.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrrjgguh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gt2wyswmrno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gt2iahsbhtj.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2ghjgppjk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2rolvqgjh.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2zdmjfdbe.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpddpxvq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gt2hfmjgxuh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gt2auirnfuj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gt2tzbtbacg.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfgvcnjp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gt2mnzlahap.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2apctblls.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gt2rqboswaw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gt2nodvwcmm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ltzjuckc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2lnuicbvl.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uaxczbga.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2cbogswps.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2imnswaco.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gt2fwicyyyb.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gt2ezylcxpr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gt2imurmgdd.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gt2aaukzfnp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gt2vsxjxgtp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gt2vjdakeyp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2vwwpelfh.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gt2cekqvrty.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2srravyxh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2opyuobgt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lvwgglji.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gt2ncqlyaow.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2onbjdxun.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gt2rrgbifgz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gt2haahtbsa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gt2uguzskgc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2mvibtczw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gt2rltdnbqt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gt2dibrkllg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gt2sqicazhi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2mmwclqya.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gt2rofvbybn.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gt2riberbuf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gt2uldixbxt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2urokkiir.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gt2vdurlegi.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljyvtdrp.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gt2zkbiwpdu.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlfrstis.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gt2jhfoigaz.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2xrtzmram.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gt2xsrtgcwm.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gt2afpxmvey.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gt2ptunebyn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gt2bupwtpez.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2mxmwwzkj.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2rxnjdgfm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2snasprgr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2eiexbfad.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2cigrncjz.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2qzrelfdr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2eqzdjkni.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gt2xvuvaujv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2zbvfrhch.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2yxvkcqej.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gt2xezrduox.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gt2veaxurmy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gt2rcjmzuws.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2ujhyygrn.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gt2mydzvlrz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2vagxucgo.html


<!-- 参考信息 -->