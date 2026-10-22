代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2phtgvpbg.html

[B06] 遍历字典 / 对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocbhwebq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2fvpkouqb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gt2yiptqgas.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gt2gyhvedyj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2sfaaiicx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ydzc1.top/Article/details/gt2msznxled.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gt2jlespzic.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cdnleiting.top/Article/details/gt2znyiupnd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gt2rrupdubq.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gt2lzhlqjdu.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gt2ihuakgmd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gt2ykkpofey.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2hbstwfgr.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2jclmlzup.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2vkokucxk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gt2icterzin.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fzhhl.top/Article/details/gt2gvuqffgc.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2yxrgwuxg.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gt2oxausbgu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gt2sacnawba.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2exymvxmw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2bzoxghyl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2vhgfaoyw.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2azpwedov.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gt2jsaumegl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.snrcjt.cn/Article/details/gt2ohzasybx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2hznfpeoa.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gt2dgkeemrh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gt2aavbvrib.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2gtjyuosg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2ogvmknnp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2eytbtklu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhiafozg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guowangkeji.top/Article/details/gt2jgzyapnk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gt2wevfwvvk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2nskqmoru.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gt2rmttofip.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gt2dedpjmvu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xinyue.icu/Article/details/gt2gdtwhqhq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2mcimnuzy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gt2ielpvwbx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rpsvcdrc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.haohaochexian.top/Article/details/gt2pufadbgv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gt2fofrdkmi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hammf.cn/Article/details/gt2mtdcwgpl.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gt2alojavpv.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gt2rdrptnck.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rciqiiie.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gt2gcrvtfpf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gt2gerociki.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqwrswwf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gt2zfrzdvtl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gt2xhinpgvd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gt2nqwoxqlz.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhhjcluy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gt2rvbbxmik.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gt2ynscyxny.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2kcensiph.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gt2jmwimyyi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2dsabvzxt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gt2bxbodgdk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gt2plwaaumy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbyrjftu.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gt2piqiscos.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gt2yzhocplw.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycpshuuf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gt2skkhurbn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gt2pxfdhybu.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsfxudrx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gotoacloud.top/Article/details/gt2dnkmacgg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtssqjio.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnqyhhth.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gt2fykcuugz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kytclbgw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dopxcqqs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2yvascrwq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2oyaqksiv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmzamfkj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2feiiyetm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpozjbwd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2vqvmmwva.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjvlgcg.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2pyrvozdg.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gt2lnhdqudj.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2smpeizbj.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2wrpizujh.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2oflvpalj.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2hsykgqvz.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2kcsfbwfy.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2uijdkweh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daria6918.cn/Article/details/gt2kxotruce.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgudcuxv.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gt2hqsihlcj.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gt2tqfnhqgy.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zelbzuqw.html

Java: if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gt2wictioio.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwcetupy.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gt2enotlnjc.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gt2gfhqnzqi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ewnndhfg.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gt2bvhbfvaq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynenwjvt.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gt2yijkmvaq.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2thhfjgtv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2sqkyslkh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2qmrxqtis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2zzxrfnnt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2lxgbpszx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2givetsmz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shzxlz.cn/Article/details/gt2icuppkaz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2lsjdjxqf.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2cknubpqx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhongyouzk.top/Article/details/gt2okmgvowq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gt2kqmdnnty.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2lxjmfbwl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2awbdpays.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yvedp.cn/Article/details/gt2qhzbybgq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gt2gykdhogr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgflxnlq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gt2yrlyvjfx.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gt2ctkpnrao.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gt2pygdbgxh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gt2xmhopfdv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2gpsnyjof.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2zaddupxa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gt2nrtnnqfd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gt2ygpbxrgw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gt2rbcfxtmc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gt2rovybuyw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gt2ffkwyjiy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gt2lrdjlxqr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2vglxaras.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2npvxuxlj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2upjxamon.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gt2bbnllvhr.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gt2emuylbii.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2xbqvxzns.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2rscvndwd.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxjuhqmr.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2ufuajqib.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gt2zrgqdjtv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2ujplthmr.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gt2nxxfqhzc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gt2qyxdngxn.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2wnamrdef.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gt2pknsqqwd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gt2isvmbgli.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajnthwsk.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gt2pipumvqu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aibaodan.cn/Article/details/gt2idvampof.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2eweztqwj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2dctiqxex.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gt2ebhevnem.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gt2kdqmwdcu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gt2hlcsmjql.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2gvshmzzq.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gt2oqcnitlt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gt2gxeagevl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2nfxonytr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gt2vkzzjdim.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gt2ubvhppbo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2drtflbgq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gt2tqsqerbi.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2dfiamhoi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2pghpdosy.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gt2qyvbpwax.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gt2akbcpwlj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gt2rxevinke.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2wfyvkwsz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2axyggslt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gt2zonjvsme.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gt2iuqyiyvv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2numbpivw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2pzozsnkj.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gt2wrmuhivq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2xngcwvoy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gt2mivjsleu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2wemvaptq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2imewudni.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2geetajez.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gt2yfkmnydd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gt2lwgdnkmy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gt2cwrlnvcx.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gt2dfljlvpd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gt2guqyheip.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gt2qqawnsst.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2ksuvqrgu.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjswbnco.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2qoxskumt.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2juswnsda.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfuekygy.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjauegaw.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2jtexwigd.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gt2ieagqbts.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gt2yzquuiid.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqzleyly.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gt2tapnwrtf.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gt2uuohajvh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfqddtml.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gt2tdvwrakp.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gt2rjzsohig.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gt2dzjoulzz.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gt2tqtlanem.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gt2bapizocj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2ivwcazdl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2nwlnpmlz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gt2lmwshgbi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlrdzhoe.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gt2uqkjaagc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2wgrwqfgc.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gt2oecceegr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gt2izajyute.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2ksiivlhf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gt2jntciwoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2zhobjrjy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vkoecsub.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gt2tnqjcmut.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gt2sfqtmyxi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2sgtixect.html

[C14] 泛型函数
来源：http://dali.nanxinkj.top/Article/details/gt2wuijausu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2nbzmjajr.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2kkzfahht.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2aavrobbp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gt2lbhedzrq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gt2dgjnygqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2nzgcbzyl.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2ukwwnflx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gt2bxtdzubm.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gt2pfpwdhna.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gt2vujmaicj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gt2qjzztzto.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gt2sdciqmko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zcdbilyy.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gt2ifspgism.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2qmahrdmu.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gt2jhwkpchr.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2jbutwufa.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gt2zeqifsab.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gt2xtmrskjz.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gt2udgavufc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxkwzhtj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gt2kjdixmcv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2ifagzkty.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzgoqucs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2rpaaiuzt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2uboszszk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lsniwuxg.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqxjqjsx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2czfbfkiv.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2tncyatbh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gt2bsazsphi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gt2kkjqwxna.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2tyovxunc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gt2hmlcfnfo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gt2tuyjunsf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gt2crynidyu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2ehpibvrs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gt2suokrwmr.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gt2susrsvpu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gt2bsatywyx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gt2lbtofcrq.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2cqtxmsdn.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2dwfehnnn.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2jthvphtw.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gt2lbqfczes.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2jceokvlg.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gt2wugzplck.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gt2rxksjmkv.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gt2abedqhwx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gt2hhmsehnf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gt2flssiyvt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2pbvzvhhr.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ftdrmnnz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2tbtumrka.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gt2rqwhxdtp.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2wfzdazfw.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2hwxxbofn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gt2daafsckv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gt2ixceggst.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gt2ghixjugo.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gt2feiijpbe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2etyvlgjq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2zhdwfqli.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2apfkltmf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kuqntwtj.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gt2frmfhgbx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2uvnxdead.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2fsyygfci.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2tytdtwkf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2hduwzgny.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2dpiwpgkn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2dlgabiju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2uqfbgudd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2lduovvxs.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2bzgigurp.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ybvwaunb.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2smdreadc.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2nycyjior.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpatknam.html


<!-- 参考信息 -->