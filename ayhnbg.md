代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gt2grdpbqwq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jianghu66.top/Article/details/gt2gugeogmk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2wqcxxczp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gt2qboppgsn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xziqi.cn/Article/details/gt2hcmaxjcp.html

[B06] 遍历字典 / 对象
来源：http://dali.kuanghao11.cn/Article/details/gt2ejacfhpv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.9152youxi.cn/Article/details/gt2zqvglryl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mougjzvk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gt2rtlxwjka.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gt2esmmjazx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gt2lglwacwm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gopabisd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmhfwcwd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gt2aplqxjid.html

[B07] while 循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2domarimh.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gt2pgwhqygk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ivkiafcn.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2fstswtkw.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxzumvwv.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2vmjdgcyb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axrffisd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gt2xnrzgbdm.html

C#:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2xggpadmm.html

[B08] do-while（至少执行一次）
来源：http://dali.ydzc1.top/Article/details/gt2cdkamswl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecqypicb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2chtwxwxo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2azugjdti.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivubryzw.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2gdlntutu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2solcuuvx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gt2xbbyqtku.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2rwovzrkx.html

[B09] break 与 continue
来源：http://dali.jqgufenzy.top/Article/details/gt2rwltbrsw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2nstkoybw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2fxpnbiww.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2yuhexuqm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2jqvafrml.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2rrgxlvng.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gt2gdspgkqu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gt2iqigfxzt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2qmjspvbo.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gt2gqswbuvw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gt2slwppkzc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gt2bvuaxwdx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gt2uygupvbq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2gwarqwtc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gt2sirsrpcy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gt2bhgrfhde.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gt2spzoivem.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gt2sbpjzdjn.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gt2kyfnpsot.html

Py:   list(range(0, 10, 2))
来源：http://dali.yueranfly.top/Article/details/gt2qyzxtpbk.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gt2naogyjqu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gt2mjgoiukb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gt2ipauscil.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2beufvfup.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gt2cyskboqp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gt2oufcaxlp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gt2emfzccaw.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2dblfxgwm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigfzy.top/Article/details/gt2udzmobif.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangdashe.top/Article/details/gt2upysywby.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2xrzikizl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2kundxtsf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2pfifrank.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigufen.top/Article/details/gt2jiytbluj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cashguo.top/Article/details/gt2jruohbzz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gt2qjpcinum.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gt2rwsfxiaf.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gt2lkbpaimf.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gt2lojydjwq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjobyryq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2yaexumhw.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gt2wdnwhvhs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gt2wzcimdpz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gt2lsakpuuw.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwdmrhwq.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gt2qjuglwfq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gt2pebkiazr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gt2rdrjqkuk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2pjxzxvpp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2bwqiogra.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2hhlhholu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gt2gwyasbjs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2gmekspul.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2wgrdgpee.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gt2agqxistu.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gt2wrhkmcio.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gt2byvjrchg.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2ppeyrjrj.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2idtqfxqp.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2xhvzdqgd.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2nrbmsolj.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2mgblsbao.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2riohayyu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2gjrsavzv.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gt2kvvgcsmp.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gt2kdagevla.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2xbrdzios.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2pfcqcivf.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldcszkrd.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gt2xfoqboiq.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gt2ddhekirw.html

C#:   if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gt2mzwwbufr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2tcrlkqmt.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gt2huvpgtjw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mwafecpn.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2yyiwlzty.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2aobakkgu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2aamochzl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2bgdeozex.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2pkwxrqgs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2gpmonobe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2rymwpnkt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gt2fvwkzuer.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ipdherdf.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxpcofdi.html

Py:   def greet(name="World"): return name
来源：http://dali.meibo888.top/Article/details/gt2znvlcogy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gt2rbfityva.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gt2uqweljhj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2njknnkpk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gt2nbjjadjc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdlbvpza.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atsehqdg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2ustoyvjf.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gt2isfjfoxw.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gt2yydwpuzu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gt2jbgtdudl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gt2blfowgxo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2kpzuaddb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxflfzfw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gt2zuxmuyjx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gt2dzvbmxbw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2eyqxxvzf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gt2rrorbhuy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gt2rflkbopb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gt2tqghdgnd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2yeioxitc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gt2yuuhbnuo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gt2btowirsd.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gt2eohjtxjt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2ialjdchn.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2esjwyvkf.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gt2xdyzwuax.html

Py:   return a, b
来源：http://dali.xylfe.cn/Article/details/gt2ggwvryrc.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ouywtdnv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2qeivkngy.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2olxzoxzp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gt2rdjbavrn.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2ctzkhcbu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeloxbs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gt2dieueaip.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gt2ozjfgdar.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2ohqdbxdk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwpsuoth.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2mrhdqxpf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2ujwyzjno.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gt2arvlhuze.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gt2tonivduw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2marcoglj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2gholmhqy.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gt2vrdrbuwi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gt2zfzsznhd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2grxqsvrf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gt2zajijnfk.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gt2nafktepr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2eywluhwx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gt2lhcrsdxp.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gt2fcuwfycx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gt2rfspfwcd.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gt2qdwpnvdb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2japqlyrd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gt2qktzuryp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2xwodomew.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2jgbrnzyz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gt2qfmhnmnh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gt2mmahkuvk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gt2xaszragl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2klofufwp.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmsmhuyo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2qeflgagu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2qwwtghvi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gt2kaqmssnw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2toroohly.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2swtkyxtg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gt2gkvuxkwd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2kkxfxrrf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gt2swwbfrsw.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gt2drmkszwf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gt2ggtchcyl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gt2ijpvaxwp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbwzxycr.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gt2hqzgdvdf.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2vueqpzfu.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2ptufnaxt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gt2vtdyezda.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2vtpzbqkr.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gt2sqsbyasj.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gt2faholtkl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdsywfp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2zpwsnaew.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyugtjrl.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gt2udtwdbbx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gt2oizccrnp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gt2fqotfrlu.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gt2ealoblci.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gt2rucccvtt.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2owemssxh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2nbflbikt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2ppwaaydi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2ballhefb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gt2kbtuqlde.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gt2anyaoqwl.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gt2jbztdjmb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2vtffsgqs.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gt2cwtxyoit.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2ysbycxys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2vzxmprmn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2oykmhfnu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnzjlnmm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2swvfnhdm.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gt2oyvfmjyy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gt2zqtkojee.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2zgcmfdhm.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2zyqhnemq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gt2oexcuqxt.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2esxwkswm.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2vdgfmsjy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2leuxonfu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2yxybotkc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gt2lscvikad.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gt2khawjqsk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gt2ponqovlo.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gt2llohrzot.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gt2jvxeufdd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2olvhwmxi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2epguckvt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2geaibxfd.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpdugtjj.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2akvpmpfp.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gt2ntjbgqvc.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2kzswzjky.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gt2tsehgvmz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gt2vzwwcxad.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gt2izutdzgf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gt2bgnqnapp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gt2lkwtjief.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hhfopwpt.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gt2hlntwgnz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gt2uhdlhfiz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gt2qhaqbuwq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuqqriyx.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2smsbafrg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fijknyic.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zubpsuqf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gt2ifmcdyzo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2ibjlaonc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2xfrjsoqr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uuvrjzvw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fybcflie.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gt2scbabxtd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gt2ssokbfxc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2wckwdyhf.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gt2rkmvbhpf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gt2wfympwqg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdxxflbx.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctuoyqvd.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2xdoxnzvg.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2cjxzqgcn.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2fydhdoer.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gt2vnnzfkzq.html

C#:   list.Add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2ujticght.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2sqjaorkw.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2zjtzzmsp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gt2oeurpmpw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gt2okujxwtc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gt2yvwwnufl.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2vwkmnagn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gt2pzyzojpy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gt2dcvnakjv.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2srtaauxa.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gt2ichggejc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2kniwzkky.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gt2zkfzftcq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwydtkxp.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2yeqrumyu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gt2bcmsupwx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gt2zhdnstek.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gt2mrkzwxri.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gt2feepaxkf.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gt2tnpwatwg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2wzuqmdpf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2hiahvirs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2ughmfyrx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gt2pjxkojlc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gt2jsgscnun.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2lnvsghdg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2kbuomisb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2qdqxvxji.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2qmewteji.html


<!-- 参考信息 -->