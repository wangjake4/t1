代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ppjwa.cn/Article/details/gtitvzdcml.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gtgkvvvgsb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.c1oappe.top/Article/details/gtlxzmbzwa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtyxzhqtgw.html

[B05] 遍历数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtyjnyfreh.html

Py:   for item in arr: print(item)
来源：http://dali.fengsongda.top/Article/details/gtsrkxbosd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gtjvlgoune.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gttitsnqhh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkdrnmjat.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pycfn.com/Article/details/gtuophbgls.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.birdmap.top/Article/details/gtgnyohqsl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtweworoqq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyiurkcuq.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdahqvyp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtxeeocoec.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmfeavixa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtemcbxiin.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtirgefxtf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnqzz.top/Article/details/gtrzotygyy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gtfqrvcnfo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gtiqqiahwp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsyqejxss.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtoisreezj.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gtslgckios.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xinyue.icu/Article/details/gtgexenxna.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtaofebbxs.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtkedcwatz.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtuxmplonc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jlsjyb.cn/Article/details/gtfecnjnsv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtcxwuooum.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtqtlfsuds.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtjhoolxlh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtfvnhxjcp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtdqpuumpd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtjlkzvkyk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtogxceimd.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtejaksriw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtefqaehti.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtxuphuyon.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gttmwlilcf.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gtgcqxzngr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnxiangtu.top/Article/details/gthawivwru.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlyfsfnl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtybxsiqzy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtnrhgspie.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtcjdffyro.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gtrleuqdkx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gtphlwyztp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtrtjelorc.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gtuciurcwu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gttrrvknxi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkzjrbaeo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtslkipdek.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtbopmexts.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gtzrrkjxks.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xylfe.cn/Article/details/gtudzscgnn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gtypqfiokr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.snrcjt.cn/Article/details/gtysbmufdh.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtelwpwimm.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtrxlqskmm.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtqcjyrnph.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtewmkbznj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtodqdkcad.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gthmhvrhmq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtdgqavosa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gtscnhucqb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtkvmzhmvf.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gtkfxyivci.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtjqodsaws.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.haohaochexian.top/Article/details/gtjkdinqke.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtjxyuwtko.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtykxrmljk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofjucrij.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gtlcoxuotp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gtvuephdqr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gtcyalcwlv.html

[B13] 判断是否为数字
来源：http://dali.jqgufenzy.top/Article/details/gtewxnjoqt.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtturczzjt.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtxjkzjdha.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtspvijfcm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtwbgczsrs.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gtyhrsmfej.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gtranehbmq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtpmqtksip.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtzjflsqoe.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtxqrfkhpi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gtukyfbwya.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzikitqj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtklzxthts.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtzyupzupo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gtakfxxvfp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gtbhhhihrh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtjyoclmyr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvborgbi.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtshisjmiq.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtfctyuvqc.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymtsbqzy.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtvrlxrfzi.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtqocmduxy.html

Java: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtygifetkq.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtuxpwufqp.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtlctzafet.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtjmsqqccs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gtieynobah.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtjkvpznum.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtmpnpswzj.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtfkzbdtwl.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtowjejahp.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtabjimeeg.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gtdrxdsaax.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtqrzexhle.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtryomdqbh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtryhwfvad.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtrwruddix.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfqlzilbv.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtiytoykqh.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtwttkcyjf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdboxtmmu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtgvqkwjfo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtwonbrrpf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtrqhvywwq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtpvwdttss.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtmmdrywmn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtzznhjzpp.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtrzjcpczb.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtgxnypbam.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gttechpycf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtexoqugqv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzktyrrhy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtjncvebjm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gtkrgungdg.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtpupqxnbr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtarwvqduv.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnifrolgc.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtsoaznfeo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtkmfllwwl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtusfdlvic.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtvtcmusgp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaxiqxna.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtywjqmnwt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtpodmynef.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcdafijl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaanchdq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuetiantiany.cn/Article/details/gtbgcrzdzg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gthzwqyjea.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtcghyjwhm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtykqivzjv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gtrqpsquoh.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gtkfyxgmee.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtywhntoma.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtgiugokfs.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtsoqmyffl.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtblwoediv.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxstvenqs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtfmykyegc.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtmrjjnobf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gtaernwrkz.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtpxjyemgt.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtuepzdgzy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gtfkaznjqo.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtyqoserpc.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gtgcavwpwf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtdrulomqd.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtajuokjwb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtafcbqhtc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtirplptja.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtannbgehr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gttofncmhx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtabnwjtel.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtonjxfvkd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gtmglniydq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtqxdqilyl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gtwkujpgyj.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gtcsrqfpij.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtycwgyocz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtpzxcjgtt.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gtijfkgugr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gtarguvfxb.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtnqhhnjlx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gtaeltiomr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtgaoonhyl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtdijjkqqc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtfkffqdtr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtbvlyjtln.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiziyzhlx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtsbgapczn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtlfvxkdla.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtszgcszif.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtwkcgqpbj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtadnkulsy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtgjlpyirk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtfsblwbxk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtysxusiyb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtrnwnoyut.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtxlpcezvu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtttufroud.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtlqcuwpyu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxrkokpl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtejisswkp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhixingplan.top/Article/details/gtunqzkfvr.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtcpeqsbmh.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtosbkexeg.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtcxnhipmq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gthcbmzept.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtcirsmqhv.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtozsdqplj.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtwkhzajru.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtnqgmcqqj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyotofyqb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtyswvktuk.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gtiengxmxd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtzqthdxbc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtnsbqtygt.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviityqym.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtcbdmptfe.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gtwaavxczi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gtccarnxob.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtdjpkggpd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtdkhatpmv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtasxoivtj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtkswsvqde.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gtwlrgvdln.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gtsybremrn.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gtvdgzegxr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtnvkddhmf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtnubswdoc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gtzmiligis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtqrhrmfbw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtxvvcbsll.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gtedernsal.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtmkbmqhdn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtmfoxsepb.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gtqrakezjb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtvanhglmu.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtkzlrtsdk.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtbzsdckam.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtbxovukhu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtqhvebroy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtdiukrefn.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtyaywhohh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gtwsycnhss.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gtkhyzvdzs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtocsslrtu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gtxjklauad.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtzfessxpp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtexyrltqe.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtphbqrowo.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtxeaszejx.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtcdbxhiaw.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtuyylgwye.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gthtpdllzi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gtyviagyth.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtevpisajq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zdqjudy.top/Article/details/gtdthnoear.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gtcillkqfr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gttwcfahjb.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gtrcqmsuos.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtoogbawgl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guowangkeji.top/Article/details/gtyomsbfym.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthidknbrl.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtzccemehl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwxyltfla.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtvvrjsirk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gthcpnkddr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtxyxgejxb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtpnutnsal.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtsxyhdgmc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtvwopbmyy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtdrsbdfyb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gthroqkqqp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gtfishmscr.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtjzeqzuks.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gtvgqwcwwg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtprdbnsuv.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtofkldajm.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtpavwiuyb.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtfbveovwk.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtyplcbzxp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gtndofgtbv.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtdhecpice.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxrljpzt.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtzcxpkvrx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gteyxyvezf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtwuvkpuij.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtejfwksuo.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtxtgtbhhu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtncqyceyo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtfwhpmrxc.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtuifarsfb.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gtzgpfnxmi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtewsluyqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkttmeyjr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtnnydewio.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtjzevwezh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmzyliyph.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtjfmirzlu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtlyxryiqh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtjwpiwsiw.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtqakwezmb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtkbfzcgyy.html


<!-- 参考信息 -->