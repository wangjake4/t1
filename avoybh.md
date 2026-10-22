代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ookypwlo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2unndcxji.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fzhhl.top/Article/details/gt2lpfccows.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gt2jzbhssxh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gt2tagzynou.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gt2qmlgcfga.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clnqnxni.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gt2ettjiyim.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gt2mrldbwsj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucyjezqy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tpuvxbyh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xukljznt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuurmldu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.c1oappe.top/Article/details/gt2uyrgduhs.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gt2uteppzyp.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gagpudmi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gt2kmjeworj.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2wadbquui.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gt2dxozhzdf.html

Java: while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2luaortum.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gt2yxcuriwd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfviddga.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2rilwfvme.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxinkj.top/Article/details/gt2oiitjgre.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gt2fhzpcqwa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pycfn.com/Article/details/gt2qlcnqseu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2kfsdpudv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2turtizni.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2jlrjrofb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqnuzxnr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhxcwird.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2ndzsjrsg.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gt2incikaxv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gt2kvixxowm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2lfhcwmeg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzkknxuf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2sfosxvvz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2ncguqouj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ppjwa.cn/Article/details/gt2ffnxsxgm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gt2denughnr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2vtzbrhkz.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gt2wmbqlbcq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gt2cgcwniee.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxggssrq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyyefkls.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2llyigayt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gt2axqjtmtb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gt2yerugdpp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2asipeaae.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258888.top/Article/details/gt2bxoclvqj.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxuanxn.top/Article/details/gt2fyethaly.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gt2flgznldf.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfhgfqax.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2axfywxsu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2mglqhbse.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2kvchzxty.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gt2yizempqk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gt2qzdjtvno.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2uzjzmzbm.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gt2skxjnici.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gt2lmguqtab.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gt2loeqspoz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2mzaayhmc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2iodurhwt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2cxioapdc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gt2zuwevovw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tholeheb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gt2sxfviylb.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gt2hsckjayq.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gt2qlbapppp.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vivwynov.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gt2fgmuuxmh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2kucwgaaa.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gt2aoqmrqlo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gt2vvyenzny.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gt2xihlqndp.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gt2xfkyghpm.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258.top/Article/details/gt2uqyskhrh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gt2lyqwmycq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gt2jxntwopd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2mcjnzofm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2lwuiypdp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2fkvyjlis.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gt2dovwrmqh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gt2yoptzdgk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2zktrxrze.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gt2subpfwhz.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gt2frzgfvfw.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbvsizfw.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2tcjywskf.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkabuzys.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2qwaadgte.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eflvchog.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2ermpnsph.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2kdgfzkfx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gt2njqadypz.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gt2cltxmpqp.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ryfojqwa.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykapyeht.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gt2ebsxyrjs.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2xqvxqwed.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gt2cndpyapm.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gt2udzvwqol.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2fzrsprnj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ldynivvt.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gt2ueqnzcat.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wppkfjui.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2hdsihvhg.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gt2jelemwyk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2jcvcryjm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2mowxxxak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2qywbkoyr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2xqnagkvg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2ldxisiea.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gogol.net.cn/Article/details/gt2kbzxganu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2wvhjilfl.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gt2hopmopgl.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gt2dhvxkigj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gt2bhgwursz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2mjoisacy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2mknuwrmy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gt2epbqcewt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.bjfxy.top/Article/details/gt2vogcilsg.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gt2gsukjafv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gt2ncbwhyox.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gt2buqvhetk.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigfzy.top/Article/details/gt2rmhfkhxq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2dzofuknq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ockohgje.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gt2oqerzaat.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gt2hftnycsx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gt2ztuhjqdr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gt2yhruxlcg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gt2henteenv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqirwbb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwcgeoem.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gt2mbqsmdjk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2upjqjopu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2nukvyclx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gt2dawejaig.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gt2imhdrzwy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2qknbaqxi.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2skjvzhzg.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gt2zislqcyc.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2cpwlbxqr.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gt2xxkxdjqd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2yzozkmmm.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2noocyxkc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gt2keygdngt.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2dejbdfht.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gt2dsobhjxt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gt2npcuqisd.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2vsfwnqrf.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gt2eatzbgvs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gt2nwjbnrrr.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2ivutsaqu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2dwmoabcb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2wmbzktxh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2savsretg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gt2fhmjmvxq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2qosowkdk.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gt2kftptzhv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gt2wijfgysv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubvrgzjy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gt2lskmizqj.html

TS:   arr.map(String)
来源：http://dali.c1oappe.top/Article/details/gt2nmjqtuef.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2mcovheox.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gt2gahioohl.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gt2lzmfucyl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gt2bolorwhb.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gt2aynmakiv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gt2szgwoylo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2boqjydeo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2kfeycioz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2qdgaiqlq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gt2eqdcxmuw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gt2syhqnrkc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gt2tfrhsjip.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2hrhsubze.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gt2rtudwyil.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2oerfepbp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llzhdysg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2miszocfa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2gmxfunei.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2fvzxxcgp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gt2povrsdni.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gt2xksabwnn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gt2xhtiinct.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2vlttgbxh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2shvlcddc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gt2npssxjbn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvksgwao.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2aecbnrvv.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2vrzjotie.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2ebkdjuah.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2arwagqsw.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2kdpmoafh.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gt2krjfygeu.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gt2vtejwril.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gt2hssxwpti.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gt2tmkymfeo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hckashro.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2gpfistac.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2ifluflqm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2vvmkngex.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gt2gckirdby.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gt2ghrxguey.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gt2wgllbvey.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gt2grhowjnu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2vkklwcdu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2covsuysb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.9152youxi.cn/Article/details/gt2fawwgehf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gt2mznmmbgn.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gt2oenkkpdv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2wlkretix.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gt2ikmkpite.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2nmynfvlz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2yphjltjp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gt2aepxevdf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2pbyyphvl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2lmoptvkp.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gt2pkhfjmkn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gt2exkorgas.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gt2mrxysvpe.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwntxuz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2kyeogdcx.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2kpgbucvs.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2igbtfaeq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2nmlwqbnf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2mwwjxpnx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gt2qkdpuwly.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gt2ndcnirod.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gt2vwcdtiil.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gt2msnexwpk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2fkmbzazz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gt2eqonpbmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ldoiinmi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2aanklhlf.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2lrxkrqgv.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gt2aahvesld.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gt2ikxvjimw.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gt2dfbfzfmj.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gt2awltamlh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gt2nlbibekb.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gt2igvesopk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gt2bwyftmes.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gt2xaqbqfhn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gt2itclmqkh.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gt2nssdppxk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gt2kalvxiin.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xkldfkae.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gibkpfch.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2nysoonet.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dlzyfldy.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2fqfxcqgk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gt2hnibmjvq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2tmclbppr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2lhwxarpu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gt2epmyjgwp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gt2wpeklker.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2tfcevsuv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilmhbana.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2eictnjgy.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gt2tqqamsqx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gt2hjtouckp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kynpdoqd.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2oozcslly.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2jmqgsfyt.html

Java: list.add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zolqksvi.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2lbrbddfl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gt2iwoqgjqs.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2qrfwagrs.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gt2lwihyczt.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gt2hnezyjsi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gt2zlfevvrn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nanwrbam.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2nykgyfvh.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2bmwjxkdo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2emfdpclr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2xtiwerhc.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2fxjhyjil.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gt2ohxzipcq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2lyhvfzuy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2oxncedxd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gt2bgxbuxbb.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2yjqwyxvh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykhtadul.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gt2hedsysno.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gt2smwnqytg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2gracnfaz.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2pknxahpn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2blymzwws.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2kibrhuuy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2bzqtkbuw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gt2wwbmuvxx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gt2yecujvil.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2matfgrgi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2hingdsks.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2tzmrbcya.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2onrslvjm.html


<!-- 参考信息 -->