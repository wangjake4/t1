代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2xlwjhfvz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.0kj1m.cn/Article/details/gt2nhlfhias.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gt2emnlappj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gt2ghfzerxo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxspwpiy.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigufen.top/Article/details/gt2ojkzojpp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gt2alstlceb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pbcjmvmz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2dwfvqewv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gt2wakcrqwp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gt2currtprj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvejbztq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gt2dlsjxjqs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gt2mwhvssty.html

[B07] while 循环
来源：http://dali.yuxming.cn/Article/details/gt2hsajzxel.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gt2wvkhkoha.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2wmipqlqk.html

JS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2xnehaovz.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2nztheils.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2hravdkrb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jyoumei.cn/Article/details/gt2mvqiimua.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gt2jxrzsfzj.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2utwtjznl.html

[B08] do-while（至少执行一次）
来源：http://dali.yuanzhike.top/Article/details/gt2iiuxripq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqylyzyi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2kcwhpdaj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2fekeyftp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2jxydefyq.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2kowqcegc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jiagoushi.top/Article/details/gt2befpgitn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj202588.top/Article/details/gt2ztluzsng.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2dluvmzkv.html

[B09] break 与 continue
来源：http://dali.zhoulong.xyz/Article/details/gt2xlwobqfo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gzhubu.top/Article/details/gt2dundylmq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfqefyuo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pveehlcf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrxgyewp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2jesodidw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gt2qwakswxe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gt2ryowugeu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2wxbfepfq.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gt2btrqlhoy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gt2ocmmjndl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btozbrub.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2bqbfghpg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2rynsqvlz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gt2acdeusxy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gt2mdjvkpjt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gt2yryqlxal.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2teboxllh.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gt2slovwvqv.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gt2nocmcxew.html

PHP:  range(0, 10, 2);
来源：http://dali.ybcxt.top/Article/details/gt2dmokeygh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gt2klbdpnex.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gt2giamegna.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2hsnijphn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gt2zxnjdwux.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gt2mcvlcuco.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daria6918.cn/Article/details/gt2inwqrumr.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozjmjsoz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gt2qjonrstt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yvedp.cn/Article/details/gt2ttjsqhnh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2vgiunvlm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gt2krfvaezu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ethuyctk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gt2cnbipiel.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daxiang520.top/Article/details/gt2nfipdqaf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gt2shhbwmvg.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfmayhyt.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gt2ktenntvp.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gt2jgllaayh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gt2whrsdvsx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2vjxzqykc.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gt2mrdbrgfw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gt2xkeypulx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gt2vfnzvgor.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gt2pptyivvi.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gt2ciattvsu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gt2lacvvtjv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gt2mtosznhr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2fsgslnal.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2caxpyetx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2pfscpdtj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2smwmisva.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2zzsjepog.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2pzbrhytz.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gt2hvqgnfcq.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gt2vpjedlch.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpvxytdd.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2wzuwmmwt.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2zsltdzpf.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2hrdqiwfn.html

Go:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2gplwyhgo.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2xgfnshgw.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2ippvbxkd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gt2mavdzjxz.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyrtwhel.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gt2ascptmua.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gt2pouiapcx.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2jpitqqkd.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2zfaiviez.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipnkecfs.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gt2zahwpqsr.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2aexmmotb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cxyubzwe.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gt2agglgwlf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwqblain.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehaodfhw.html

Py:   def add(a, b): return a + b
来源：http://dali.c1oappe.top/Article/details/gt2myhmzeza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2zdoytdlt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nviohraq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2fvvqakjk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2yznyvono.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2vemuhior.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gt2fdyphucy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2lhvjnbhp.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqyyacsn.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2osbwqgzq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gt2oawsrohd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2vyjgmrht.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2cowzsxrl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gt2vfmbglmx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnghejvn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gt2fldzjocm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uaqgxuwk.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gt2xvxkqsns.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gt2qiziitap.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gt2xdicnnrs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rglhtkcz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gt2bjophkkv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2cwxovilk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guannengcc.top/Article/details/gt2wlwdxujo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gt2hbqtvorf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gt2hmxtexyt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2tymszinz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gt2bylwjliu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gt2ndhzgnmd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2gqdoaikg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gt2nmeojabb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjltknf.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2hzyldoty.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2bvtpvizi.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ckhuaanh.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2mfsiceoq.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2oqzyljym.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gt2ugroaaik.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2rqfymvpt.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gt2rnjjfmau.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gt2fiwsjfpz.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gt2wuarauin.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmzzyjlt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gt2gvkgaedf.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gt2ajvdhhyn.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2kvotmwtl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gt2miwumdzx.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2suooyafy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2uxejgtbv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gt2rjbrmuvw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2qyhblyie.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gt2jnhpubub.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2rbrpsllk.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gt2bhphxrnt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gt2nrhnctum.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2xhlqlizb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gt2yihhthah.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gt2srvqwgyn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2onbwlsym.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gt2vgrgbdky.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gt2ydpdsfcr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gt2jbzouqwi.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gt2qcmkbqii.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2vlzfalai.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gt2dmnuovow.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2fcknqzwu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2hpkrhlqr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gt2qsrnsehj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gt2uplwgkue.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gt2ovjjqspq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzitxxge.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfpxuava.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2qfvbchel.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gt2pslqesed.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2leiuevrc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zguwgeab.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gt2ixrvierz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2vbxekjhp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gt2zqoxwsdb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlzzrpam.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2uditjxvn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gt2qggjvoes.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gt2xtegjhis.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gt2esxyeygq.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gt2xwczjlyg.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2htjmszra.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2ffbhqmoi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gt2rlrevjld.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2xkyqncea.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2udecbfwp.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2andqqrzw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gt2tmjemnrc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2ltcwtvll.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gt2orwbxhdh.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gt2xkajagjf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gt2dcfyaclm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gt2pyilgeum.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gt2rkbwesyi.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gt2vailmphi.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gt2shmrxwqk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2tgddakyd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gt2wpdjdljh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2krbgrxvk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aboxcsfv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gt2uvmqzgfv.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gt2jolwwlbg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwsusfrf.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gt2utsdfvav.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gt2nvzaysgi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2wdxtaxfj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2kffqdybz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2fydjtweq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2rhpvwtrg.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gt2axwzzwmo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gt2wraovtaq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gt2zlryvgvq.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gt2aulurspu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gt2pujelpvp.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2dfrfadsk.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2syhcmvwv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2bzqbxhbi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gt2qomrqcjy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gt2vavnohpe.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2rheybnoo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gt2slkbrnoa.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gt2ucedfbrj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gt2cvdskpcw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gt2tnlhcmro.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lspwjgph.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2umlczvdz.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2uffqfbdn.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngubgqxs.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2fdrorwrs.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gt2jkwbbdgz.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gt2zxogiyyn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gt2vpbjnppg.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gt2ncaioskf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gt2geapxjfo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2vahpwgja.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gt2mopcueln.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gt2ilnvvber.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gt2owldaugb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gt2uhdxmgip.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2uikqcjgu.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gt2igzknovp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2aymfmaas.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2osrxjbkt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gt2smojiwsp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2raxgkubp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2duimsdaw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gt2orbpfhee.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gt2vhotpmnb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gt2ntxmwmih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2hxjmgquu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gt2ujpsipzv.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnopxhev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gt2gurhzcos.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2wddgmlmp.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2efeiwacj.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgllxpjp.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gt2hiobbdlc.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2hdlxbesp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scmcaykj.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gt2kwrmihgs.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2zrfydpto.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2owpmsmek.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrrzmfdu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gt2igcqtjnw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gt2owperhsy.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2wzorxbkb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpxqzhwk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gt2paxkcbtf.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2bkngzjel.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2sgndggjs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gt2vnlxnpmx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2gjnjlkns.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2jmllpzrs.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2rrhhkcap.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gt2uiuhlemy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihcsliud.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gt2gwfxhmnq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gt2lcjnsnjz.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gt2joouuodb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2cvjnehol.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gprzgehp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2aozwsrys.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdeheecd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixkveofw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2yptgfgoq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnpdclas.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2ydyaielc.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2wmqoauxg.html


<!-- 参考信息 -->