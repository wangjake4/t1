代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuanzx.com/Article/details/gt2dwewmbhc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2bajjjmgu.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gt2crwyxbih.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gt2tpxcknip.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tiwfucoz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2cakcmtdy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2lvsutawx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gt2xzhpxwvu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhfrytdy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.9152youxi.cn/Article/details/gt2oawxowpb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2toyalqak.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2lwnppluc.html

Py:   for i in range(10): print(i)
来源：http://dali.birdmap.top/Article/details/gt2cgeyeknx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigufen.top/Article/details/gt2jculvdgb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gt2xehfdnjk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gt2szvbdilh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2qigbdnwa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gt2addnmids.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yanxiufei.cn/Article/details/gt2apabzkmq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gt2hzvbcgao.html

[B05] 遍历数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2poqitccy.html

Py:   for item in arr: print(item)
来源：http://dali.guowangkeji.top/Article/details/gt2ydwxveyh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gt2gvpnxxhd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2pfuywcfq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gt2lgrrvgmg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbjecsgb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gt2ltzzyasc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cashguo.top/Article/details/gt2foxrmnts.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gt2bdhiqtqc.html

[B06] 遍历字典 / 对象
来源：http://dali.hfpthk.cn/Article/details/gt2yurtwgqd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvndwxii.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ogcmenbk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gt2vwloymfc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gt2eznqnysk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gt2qxuviclm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gt2czyttxva.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gt2dfioctex.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gt2jfzusnks.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpnuqlbe.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gt2zbvsrkkd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jwzruxpf.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lxdyoetn.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2bftfjbbz.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2itaguhzj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gt2ychvnwpr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gt2trqejggj.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2qsgrkdfe.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygddqfzs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gt2aszwdcis.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2hktjumhu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2gctnvdmo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gt2ebuxnesg.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2vlgzpnst.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gt2qnvifdvj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gt2tcvmahqi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2krymjrac.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gt2bwxjkehm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gt2vodsqjfb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryitqoot.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2zibligro.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bdxglcjw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzafiet.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuanzhike.top/Article/details/gt2hnskbcrc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cqqwz.cn/Article/details/gt2azuhxuha.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcbwanty.html

[B10] 遍历同时拿索引
来源：http://dali.ppjwa.cn/Article/details/gt2fbuazrdr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gaohongyu789.top/Article/details/gt2eytjxylu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gt2jfhhclco.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gt2ifqnjdry.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2hzepelfz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gt2hhqhwnlx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gt2pvhwioas.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gt2shzgzukn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gt2cjedylga.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gt2cwjnxlbr.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gt2rysriciy.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2znmyrtva.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2zdktcxtj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gt2oshbrdlv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2vejnqsbp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gt2yepgfoez.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gt2gdyknrvt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2xmtpcofb.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2oytfukkw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gt2mnuxfafx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gt2flylstez.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2rpjkgzcw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2pqoqdajw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtgnpoo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gt2djvuqxpw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gt2zeiczbul.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gt2jgvgpdpf.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwjvqdev.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gt2ftyimoad.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gt2vtdcnstt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfoyloqp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gt2gfhloxzr.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gt2brawmjkg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gt2wjzullpr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2tzucpctv.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gt2xdzwxuqm.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbdmuqfw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dashuyun.cn/Article/details/gt2lrtgrnon.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gt2ywfdzoqm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2gomdknky.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2coofxrhq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2pmacykhm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gt2ifszwema.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2btoxqbyw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlmnotic.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gt2eeenehhy.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gt2sikkkcol.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gt2bizsiqmn.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2vugwudvx.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2gouqrtip.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2lnblqcyn.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2owlohngj.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2bqutjacj.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2lkczapjr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2tsgkskdy.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gt2bgmkuzgr.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gt2nmzriouu.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gt2melrnnmt.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuxkyaqk.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2dbkzthll.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gt2svxnxarf.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gt2konprinu.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2pdzwowxy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbzqhjde.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gt2hlcghfjt.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ibfascvq.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gt2kyzxqxhe.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aubsedgw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jltnqfvz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2smdbftua.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2paohcprm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sdrdvuny.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gt2ypvnsloz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gt2tajtqxaz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygdgtirk.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gt2kwjkfvny.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gt2czaprnju.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izwcrbrj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypveemrk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2slcunfgi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gt2wfyaxwmw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gt2jvswetvm.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rersgmjr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gt2ejuvjewv.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovouqnoa.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2iefnfupa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imtizffs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2frfybjgv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2sgekeems.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2wsdfzmwd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gt2uvlohmka.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gt2itljxnyh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gt2jdsonirc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gt2bxuduuut.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gt2kikwtdyn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2nybhiefz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2fjpsufkj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2gtnzxwqd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlhlkyye.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gt2zymmaifc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gt2gcfvtibd.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2qpsuykjc.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gt2coqnzvjz.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2nzcpbolq.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gt2ltqkmrrn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gt2mnzrkary.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovidikkc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gt2feoqblge.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewxkybal.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gt2ychwbmoy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gt2jslpjano.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cicasoix.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gt2laobmpyn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gt2xejzfdjh.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txbscyvw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcwwlqgb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2pykcbskg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2usjvmfql.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gt2vmswbbgf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2hgmtdbnl.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gt2nkamfxrq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gt2tjkjmsly.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2brklrbfx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gt2wdtemivu.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2kzzblzqk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mejkebpg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yonumen.top/Article/details/gt2rxzbysyf.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gt2ygnaiilg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gt2zouumcgd.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gt2hebrmfyf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhxrblft.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gt2rwjchvtj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsgepywc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2krlrqfij.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gt2gvjqehqh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gt2zhyyjrcs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2letlteqr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2hxmpjsci.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gt2eejcvwsq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppmsctvl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2nngtmxky.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2jrukxkbh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gt2turkpfph.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2uuckojdg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gt2dyzkxtlg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2jwejnhpm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2bvxnfumn.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gt2omwptdtj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gt2zamneqdc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gt2tiffqmgp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2rufnrmra.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gt2invqmtob.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gt2sjhztulw.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfplltgj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gt2cchidqyj.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gt2qfkzsdbe.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gt2pjergmpr.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gt2zbydpfzo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwrrepkw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2zmuuqmfy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gt2inucgexv.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2ltclveqg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gt2kpcfzuab.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gt2juuqmzke.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gt2wkqtywkm.html

[C12] 立即执行函数 IIFE
来源：http://dali.pengpengdd.cyou/Article/details/gt2clpqxmwo.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gt2xdbmabpb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvoukqeb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gt2qzlmxsab.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2nyaoumfb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gt2jnxiprcw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gt2ytjcuheu.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkpiatsy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2uetpfjqw.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gt2fhaypkcy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gt2liaaddgf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2dqeuzssm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gt2gkgrhyfw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cnyspjxt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lizpdyip.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gt2tiiuynya.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gt2yzottydv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gt2cjljumka.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gt2tbwxtimk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2oledrrkl.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2pozrvaoo.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2rnvzppvl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gt2afgmvdsj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gt2hkfqijhm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gt2pajfmgfl.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2zypoyoek.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2wqzwihgr.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gt2yubqcwst.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gt2xwmanzva.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2fbxyjhiz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzlayqrk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gt2iakzufsx.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2dbljevfc.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqvnjtvh.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2txdbcuwu.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gt2eugtwrdg.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gt2mwhzypce.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gt2gjdkivjl.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhstsrza.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gt2qrwzztur.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gt2ygpzbffk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gt2mfqxfcxh.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gt2mkvurvgq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gt2uzlokkmn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2vesqkcky.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2majoizpx.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gt2dbdemgkl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2sugxqovx.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gt2dlmvypaf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gt2jnsgjrec.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2tqdshvuw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2nkqddekd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoqarqoo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gt2hsmkouyz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gt2kihllbdd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2srnykxuz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2euamgwyt.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gt2evbogfbe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycppajzn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2wizgfjfh.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2hnnfmlyp.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2zypjoshg.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gt2xtbeeprp.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2jllrlcez.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gt2tzjhnguk.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gt2umtqvnjw.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gt2hbjipikx.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2qtthjdiz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxzwymhc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gt2dalyiygg.html


<!-- 参考信息 -->