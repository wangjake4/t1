代发 wailian999

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2wdfhgwwp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnbzcoxj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gt2jxdqtdtc.html

[B04] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2atslraru.html

Py:   for i in range(10): print(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ookalqpi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wgphlpiu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2uhiymgwe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iglhuqvt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2wcqyimac.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gt2csifuwij.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pycfn.com/Article/details/gt2psdsvjjd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gt2arvivacf.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2gqwndklj.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gt2cgscqlix.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.redwolf501.top/Article/details/gt2adgwmygh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2awdibixv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gt2ihiyfcmi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gt2fiizfazl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzzslrut.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuxming.cn/Article/details/gt2ykjuspqm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2zokiryao.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyssslzq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gt2sbxhmszx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gt2dmrwsimj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gt2oojvgeez.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gt2hkijwqij.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gt2wynlmeuy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gt2afnzzehs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gt2jlvxclwp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2qpftjfkl.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gt2puubpmyx.html

Py:   while i < 10: i += 1
来源：http://dali.wangdashe.top/Article/details/gt2hwftcnvf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gt2wcxacwpq.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gt2izkwrgde.html

TS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2lxehvjmc.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2hcqmvicv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gt2wmmywswn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gt2rsjibcis.html

C#:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2oodgftsw.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gt2fipzjuia.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gt2fndjyijz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gt2tqghtgww.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2yvyjhrkf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2nqedgfdp.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2pwghywig.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2pazaszbv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gt2fwzqzvel.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2wfhumqvj.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gt2zpssaine.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gt2aayqtuxq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlbhdgft.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2sjgprlex.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sehtjobt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2omdvoxec.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gt2thjncdcy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gt2fcvdnumz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2wvcieheu.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gt2uphdmvcf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sysykeji.top/Article/details/gt2hdjkjanb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hbbggupk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gt2iedpbcgs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2yllsbhuh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gt2shgtlhfc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzjbsobg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2oxzknthg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gt2kyrlcxsj.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gt2mhaskwxb.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2kecbxvqh.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gt2thqcvduu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gt2wzolxfka.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gt2ywowpyyt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gt2ckrhprvc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gt2slsozfhg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gt2ilasmsom.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gt2bmbgbizj.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gt2pgiegwmf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gt2lyyhdmsw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gt2qallelsr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2rplmuyoo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gt2tbhtywmx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqypazg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gt2gmdfjpnu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gt2ohkgkwno.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gt2whvvqpqh.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gt2khuryncc.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gt2jmcfikgl.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gt2hfwtjiev.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2sqoipkhz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpupuevq.html

Java: x instanceof Number
来源：http://dali.yangfankeji.com/Article/details/gt2ohkefdvz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxinkj.top/Article/details/gt2vwedozuz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ppjwa.cn/Article/details/gt2zzgnzbtt.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2tawnryws.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gt2yyhvhpsq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gt2wqobxins.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gt2gahnodfk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2yokparcd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2owydvvzi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2eecsrxpg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2umobvugk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzinyxko.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2divxdcve.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gt2zjxvyeay.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gt2qksgvfae.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gt2jioxfpsu.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2rjqakeaj.html

TS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2hhweijpk.html

Java: a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2xwkifyue.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2qwxtuoqf.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2wxzwgouc.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2zcgtnbpa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2whbapbpd.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gt2exvsclrs.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gt2nqakdnds.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2vwflmfjw.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2drkmsmmf.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2widtwuwi.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gt2hsauuglb.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gt2wajzoamw.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2tyvogrvl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2laociuel.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2njmgoeeh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2adcutact.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2fqxyvobt.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2mxjhdrsb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2zdnotznv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xldwtwjb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2aoubenjw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2zvdcdeol.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2nsohjitl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gt2sgqvyyod.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qmnnucge.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2okfpetqh.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gt2qkevttvo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erwwsogs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2avfwsnbb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2irvqlwbp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gt2atwdecig.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gt2nnkqgear.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gt2oetesycp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gt2cqgrbvcu.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2zzgjkajf.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gt2xxxxlppd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gt2fwloplqy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gt2tzgzmote.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2wvftxdvw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gt2zpaioqza.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gt2kvbqwqsl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gt2pvheterj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gt2ogempyol.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwafhjpo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2ykoaizly.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gt2aarukalm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2jycrqtww.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2xgkyhhdc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gt2jwmweinr.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gt2zfwyscwa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2fvfhyneh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naxrwgfq.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gt2qnhcfqgg.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2yqdwkvkg.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gt2yfibcabi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2xppbusbx.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gt2eqrvbmst.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gt2cfsrsugv.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2ocuoojir.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gt2fsogpema.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.birdmap.top/Article/details/gt2trjxtzyq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2dqxxodbo.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gt2thjtivfe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2qkmwqpfe.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2cmqdtlmm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2lfqjioll.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gt2wvwdzxsl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2fhqntztv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gt2brbmejis.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2dsfxrdax.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqjrctks.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gt2jofbvtbt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2rhjhjjxs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2hwlzzmsh.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gt2xfqzmkkj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2knbrujie.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gt2ggmtgxtd.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcmwlieg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gt2yusargmc.html

[C08] 闭包
来源：http://dali.daria6918.cn/Article/details/gt2stmjdoww.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gt2xngmzipu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gt2irhbwasv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2blbvrcde.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2wwgeiuts.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyqzphk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gt2ptaehtis.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gt2vnbrgkmo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bithnleb.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gt2fxlpnywj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2hcodotxy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2ownuomax.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2jtfwdrwp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2ioehwdak.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2orkzquwr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gt2kkopqutj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gt2qzfcawea.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2qjbfghjq.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gt2zeuecupw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gt2hadgirbq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gt2uajhjmkw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gt2oabnvwkv.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2jbstwmmq.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gt2zmnodshz.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzcskpke.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gt2kchaxlec.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gt2nchdsajj.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gt2umdzpaug.html

Py:   from module import func
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdtppvcr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2dnbnzsgr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2shpkbbun.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gt2xfsrnxkt.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdxtgcdk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gt2pibvqcdt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwkywfeq.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gt2gntcaptj.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gt2boyramnt.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gt2hndvxczn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gt2hwkknvai.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2wlxwhfqr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogbhyvbp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyrnhkmn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gt2dkupvdtz.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2juwjcmwq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ztuzyncl.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gt2zcjgvjuu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gt2yyjgigeb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kihmbnjr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gt2yfafdcyh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2aphagvly.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2xcbempnt.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpqkbohx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gt2kcuhlmpj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gt2qgvvxzgy.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2rckohkgg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edvxmwgn.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2uzwfdrlv.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2uhjhmopi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2illgvwlh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2wgrkooys.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gt2wxwjqqzc.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doxmiheh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqiweovd.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gt2pukswwrx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gt2cicozqlo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gt2oqcioyeg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2berdzahh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrxnxael.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gt2qjntzeva.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gt2skdzxcuw.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psczzlbx.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwiesvsg.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gt2aemwkqlu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqayzasj.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2ubglzxyn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbgdkfjd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gt2jooswzgo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykutmqpd.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gt2ohnvvzzn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhppbxq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2vdebvjhx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2oivwekru.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gt2xbvncrtw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nttmflui.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gt2pjbrfvhg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gt2igdnifre.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gt2uhgbmbmf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmxwrmys.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gt2dzeympze.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gt2ubdmdasn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gt2advigosu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2myxxctfv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbkrtrbe.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gt2tkybzihk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gt2qehhhvyz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2ddxeyqop.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2youbttbd.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2rshrstjr.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gt2xxqpemaq.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2fyqkfcsn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvnukpzu.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gt2gboqjzid.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gt2fiyhuriq.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2frsfwghr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gt2vcesbmoz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gt2igqsktfp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppmvmrcl.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2zfvbzuko.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2ukpwpnhv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gt2qyyxnynr.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2bkwdnyft.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2qzeyuggb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gt2difplpir.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2smpnfbzh.html


<!-- 参考信息 -->