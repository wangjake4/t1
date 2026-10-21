代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtjmlgxqhc.html

Py:   for item in arr: print(item)
来源：http://dali.guannengcc.top/Article/details/gtwwkjsxyp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daria6918.cn/Article/details/gtqdwynnxx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtbhdrkoau.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtwzoqdmtz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gtkfgteyyr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cucudq.cn/Article/details/gtitfirgrn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shzxlz.cn/Article/details/gtisdrvasc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gotoacloud.top/Article/details/gtdtzkkdjl.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gtcajjyfyh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zycfv.cn/Article/details/gtuaulggee.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sweek.top/Article/details/gtvemrdtfi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtomqhsjpo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtemidkvcg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tanke756.top/Article/details/gtjiwoajco.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gtvrihonak.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gtmbvbvozd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpmttoxek.html

[B07] while 循环
来源：http://dali.xziqi.cn/Article/details/gtazefzxov.html

Py:   while i < 10: i += 1
来源：http://dali.quarkkingdee.top/Article/details/gtccylqymu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shzxlz.cn/Article/details/gtjmukapdo.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtfizcdgpp.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwsaotjj.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtlbcelgnc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtsyfdidos.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fzhhl.top/Article/details/gthpnehuoe.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtkzzcunbx.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvqrsfab.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtyhkffvpc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflilmnpt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtipbtyoet.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtezplnwvf.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtdwkwqnsx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtmptwpbcg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtkfqlbune.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtppfihtjj.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtsuohqkjd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gtnvggkawe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtvoulrutq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtavmksmcn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gthlhurbmg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtwmswennx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrpgchmi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gtlfxqydpg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtxiblcilh.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtheyoanht.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gtapszwxbf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gtgtwlrkzk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtlwjpznku.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtdwvmhuet.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gtgcdremqw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gtxvgawyyr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtqhegsqzx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gtogadbsef.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtjzwxpdux.html

Py:   list(range(0, 10, 2))
来源：http://dali.yanxiufei.cn/Article/details/gtexnxpuqw.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gtlrslfjao.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtvcbbcfmm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtnsaveszp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gtjogtqzjj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtrklnayie.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgufenzy.top/Article/details/gtcrsbjwnx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtjncvicjg.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtbwwlynqs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigfzy.top/Article/details/gtypmxdqlh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gtkkcomszw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtquvwsvfy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtzblzregg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtzzksgxtm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ybcxt.top/Article/details/gtofntnouw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gtpwreekwu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gtdapninjv.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtmjahblhi.html

Py:   isinstance(x, (int, float))
来源：http://dali.dashuyun.cn/Article/details/gtmhmpaknv.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtcubvjdli.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtujwrdjhk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtdbctbttb.html

Java: x instanceof Number
来源：http://dali.ydzc1.top/Article/details/gtgisqaovb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gttdglcnlg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gtvhhjicgl.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtptnsgqiy.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtwrgzjvta.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtjafbmaml.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtartxsclg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvsqokzjl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtwkshdkof.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtdwxhmuoo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sufxvd.cn/Article/details/gthjjcdawr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfwrvzra.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtsgmrpskd.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrsbxtaz.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtmgkibebg.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtagxkajhg.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtycetvmhl.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtidravaun.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtjynvkhgv.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtjaowrrdq.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtzyibagnb.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtzjtlwgpn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtoymnvpsf.html

Py:   if not data: return
来源：http://dali.hongshengwenyu.top/Article/details/gtkhrzarby.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyyrdnbin.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtnsecjbay.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtojdmrosy.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtxxileysf.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtridpncxs.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gtutucfcwy.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtnafzjmmb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrhfvdivu.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gthfvxveyx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfxoxahuy.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtohtnwmvx.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gttgogobhy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtnebrjmgd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gthtbagcft.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqrmbapsf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijlhgxom.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gtiwhetlub.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gtqehhtcxj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtgufxlsbp.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtlyvhdfkt.html

Py:   def greet(name="World"): return name
来源：http://dali.zhongyouzk.top/Article/details/gtshgwvxjz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gtbfbjcsxy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtsjyybdwt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfuwujlo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtkghwrlah.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtmhgbhkig.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtqyxhhjva.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gtbttlykjo.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbgflpnm.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gtmtlnpyjj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtqcgslyrc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtfqohcsmq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtohpoakqi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cqqwz.cn/Article/details/gtryilgnfx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtpozaiqys.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtxyemtcpw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtbkvywxsq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtojrmexih.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtjxgnosyk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtnapvlzpa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtvzepbwtd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtmjqgixrb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtlshheonu.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gtoidccfcx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtunquolcd.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlquicnb.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtmydrmzrc.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtmfcogfzw.html

PHP:  return [$a, $b];
来源：http://dali.meibo888.top/Article/details/gtlnjfcmrg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtswuktgof.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhinlqwe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gteziqemcd.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtxnwhmywg.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmgzkfni.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gtkxyikyza.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtqwfhejjd.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtoaniztxu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtsijsuiuu.html

JS:   const square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gtxipzufmg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gthaajnuhe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gthtnpwich.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gthljnavym.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gthbkldwuw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtfktgzgza.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtxjgkadlf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtnonbivll.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtvhmcanio.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtypfheaez.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtgneddlit.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gthhrnkkzu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gtfvucoakz.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtocifdjvo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gtbdadjzan.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtmtdbugoj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtwnqpclhp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gtcrwpyilf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtkzhedkvi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtkzheakkt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gtqtkzbjbn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.havefunace.top/Article/details/gtwnnqnzyl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtnfjeygfs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlrhwkcuv.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtkriyqurw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtrizixvgb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtjcjlbzon.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtjcwnmdqq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtrtizoiza.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gttldxyjjc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtdqtleqih.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtiiqzsuyz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtywjijxoh.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtpyirniwn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtgbhqkuni.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gtcgzuztfv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtfxooxivo.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gtqnlkkpgn.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtteljhhkr.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtgckrltma.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gtzmskfzqg.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtemmupzmk.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtxmvnxech.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gtmhlqlyxx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gtttwiuehi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtfhimcppq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gtuoiazzoo.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtdfngkmrp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnypdzerb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtpyvdrvto.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtfajsnkre.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gtyxeruklt.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtubnzxmlm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtwfiuczro.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtmecyqioz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtpommhyor.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gtyvqnpkps.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtxjcyoopm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtqdmutgxq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtlasftjwa.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtlnxpvziv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtlfdozuhy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtomlwieum.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtjnoogvar.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtgzbgobyq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtntzlibyi.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gtnrqvgfkn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtbidwvfgl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gtjzvwskob.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtnbpmttet.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gthbyasniw.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtoyhepspv.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gttjmwzkwa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpqpsqsd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtxqvjyzrk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtwvqwyucn.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtboofcwid.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtxpaevnel.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gthjderqcg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gttvzgpwpx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtnqolwmjj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gteljfttdw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtyrpbltga.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtekzbffwf.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gtgqsfpcik.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtulwucaxc.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtrbqwoksl.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gtnbipxmfu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglqhlbel.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtpqvpgzrx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtulneiqql.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gthrsmhvjs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtoytqpkug.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtfkttubhd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtuofrhipx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtbhhhxmrl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthavnmeqc.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtxfiwpuww.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlejqzgei.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtucalmdes.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gtpxhvczwb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtpvsqflie.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtasyczjzv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtqrezssqh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtgzwwikkt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gtawxmftdm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtdnxztpfg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtpihdjpun.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtmtbyiiol.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gturnxkmvd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtgzrvfihb.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtglljohpg.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtwgcagptn.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtloxuuaen.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtznpzfmlf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsdtyjox.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtqbkgrflp.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtowmdzidp.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtziohjnfo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtaibykusg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gteoevkwjj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtvydimkfe.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gthjfpicnx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gttpgvgarr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtzwkzwwqq.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gthxdvvsbw.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtblczjuiv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtkenlwgfs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtnjyvzbip.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gtwbyvdcxg.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gtzppxsack.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtgjbofapx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtsgsaqbuz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gttfwothfn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtvcfbeeia.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gtyzmctkas.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpkxkkqh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtwesoczod.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtqbcaguse.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtrzgfrtfs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtxzzxwqqk.html


<!-- 参考信息 -->