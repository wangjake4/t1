代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tian-w.cn/Article/details/gtkifryvcm.html

[B06] 遍历字典 / 对象
来源：http://dali.yueranfly.top/Article/details/gtnmdgidpw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigufen.top/Article/details/gtinvweduo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gtnrtzemto.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtamixfxum.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtskukpswb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gtutmfeooi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gtslyxbgjl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.meibo888.top/Article/details/gttucawynr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjgbqrgdw.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtdhncdkuc.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gteojmwdtt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gtztpfhezr.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtaouyygpg.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsroncevg.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtwxmqworr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gtsiqpniqs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.feifeiyinyue.top/Article/details/gtsdafttzp.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtukvvxond.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gtvpqhvtaa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gtobbrkrdx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtrpzedfzn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtydqgphif.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtzlimkpor.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtkgdpcpwm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtuqbznxzf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gtvfgmgvld.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtpjkezscq.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtwbltkdiv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gtzdegfuwi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtrdsflhin.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gttkycquow.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtcwllmugr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtwzohzkfb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daxiang520.top/Article/details/gtucawbxfv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gtnhbmfsug.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gthcnwmtmj.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gtxikreeqm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhhxhwuq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttrykscnm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtiytiojoj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtplmfzpsr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gtefjvwgkd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gtwavndlyg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtjhbrfuhz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtepokijjf.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gtdphmwrrd.html

Py:   list(range(0, 10, 2))
来源：http://dali.bjfxy.top/Article/details/gttlmddbfs.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtjnkturkz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtkmvraaec.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtyqkziqcj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtqeouvfbl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtktnoeoru.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gtxlozaqso.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gttxokkliu.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtiqqocbpt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gtopvnycit.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gtgxyptagl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtsxmsbuna.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtgytcwhwe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtfxfttowp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gtrftzlfow.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gtqvvsdcvo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtrmyxkdui.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtijhtcwyq.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtinwqzcyn.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtejuzhzwe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtcdscuuzo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtaysattiz.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gtfyuqklts.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gtonyqgnbk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtceaizrwp.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtbvzxhots.html

[B14] 判断值是否在集合内
来源：http://dali.0kj1m.cn/Article/details/gteaqzmbpz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gteidfnjhv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gttlgviora.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtlqwlsjze.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtfohkfcjy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcabkbebw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtozimzvzb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtlgwoalll.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtbpbsfrjg.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gttxbfscfc.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gtuofdicls.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtkcbucivq.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtnnsinysp.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzeuieep.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtesbjxpwy.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtsewvgwmo.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gtqkhtvplh.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtolugyegw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtulttdiay.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gtbhumhboa.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtiiogmdtn.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtuhlmlobu.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtgncujcje.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtthojnqmx.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gtnulskhne.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtevwypflk.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtirpdtkfc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqfsctlcl.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gtzhfxufrm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdlcexqhh.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gttwopshrk.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gtvlnivljh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtjurmsitt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtasuroglc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtruylxbaz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtepzucilf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gthntsiajx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtwedrgoef.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtkmebnanl.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtwukebjqv.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gtcidjpgwc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtansbzvpi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtcbycgpzs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtygbizdbw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtszsoomje.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtrjfvgeau.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtewstzlyi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gtsaxjkguz.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gtlbmskbtg.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtwzyvyyks.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gtlxaqnlyx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxzozrop.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtatgsvxwu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gtzakvnvjc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gtqypebvwb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtixdtliog.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtnnwqwqwh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtcefkcwhc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtxkubanjs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtjplzdtxw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gturzarilg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gtevqtaarx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtiaupfkdf.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gthlqvqlvc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtsrptynpa.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtuhvnfcch.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gtfbwhetgp.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtpobzdrxr.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtwkgvamfv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtsvduwazv.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwphosci.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gttbbbbzht.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gttpxexeqc.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gthfhybwac.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtepfrqxpm.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtykocfohu.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtbivrfgmk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtrarawwlt.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gthksjturk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtnzkrbckg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtpjsjshlh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gtjyvbozab.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gtrupaezrp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtmbpqsaej.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gtzbusstad.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtlkysctih.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtyuxrgexf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gtmnfyewpf.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtorpekntu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtxcwozawz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gtiksxftlu.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthwohiiu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtjmvbwuyn.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtucaqmqaf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtlcyfnjog.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gtwgvwhswx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtihwsinbs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtditcwcmg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtsfappflo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gthrehvhnw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtajlyexiv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaclbkvia.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtwuptjqju.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gthtnupwhl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtumdjemrt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtayzmvmlr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtzedqhyfz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtsncjfqwc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtgzpdfjci.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtliymxmtx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtttsidqkk.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtksjsllth.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtdkrlpzos.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtioozvxur.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtcswurxgt.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gtegghlzco.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtbdvozjzk.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gttmmyodhp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtbsppvghm.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhkellyy.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtgwmwdshg.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtgkcdbldh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gtlumnifwh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtzffvbdsl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtnycnaqoz.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtcgimfbng.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gtzvfsldeg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gtnhdocdnp.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtwjbgnakn.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gthrhaxwyx.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtjgsooybz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gtfijugxpw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtkfipqnlw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtwfnhrggn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gtquyugzly.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtclkzzjkv.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtmzrvockh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtbixtrwce.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtnldexmja.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldrjtbrr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaxwjiaq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtuvehnwnj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtpummchoe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtoauabckn.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtdqmceubt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gtuzwfkqlq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtbykfrnxw.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtcafbbjkz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gtgylrttvq.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtfhwzuzbw.html

JS:   // 无泛型
来源：http://dali.cashguo.top/Article/details/gtfggxjint.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtiksegwtc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtnwuexxvi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gtzzrfvxng.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtdzapzhpm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtdxjxengs.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtwzfxolvv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtrcofjmgn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtkqyyhcjd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gttwulrdvp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtzsyckwoq.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtpohbmcvx.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtkuagrade.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gthjvluwmh.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gtqjvvzhwj.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtsazsskoe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gtzmtcplpx.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtvdlatfel.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtidavclxk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtusmeyndx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtyfjsymxu.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gttfeafufp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gtgtecmqbz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtpvawmvgs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnltgbhxb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtgmqijrkp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyqiitbkj.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtijrxdweh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtzpzfjbqw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtwvzlgkpa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtxqacbofl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gteqninups.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtiuwssdrw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtbszbftau.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gtjgdqcdxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtupcunfbx.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtlwlfpmcn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtnzdkbhgb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtdplonioe.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtwivjdlka.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtxskcjrqk.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtzgazeevv.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gtspmfoiwc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtesdnhzwt.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtemrseldi.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gteybujmrb.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyilafqzb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtuwodloyh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtkfhrfwci.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtsjnajejt.html

Java: list.add(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtriwdwmfh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtaeeqbbhw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtwkzqoyfa.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttixemedv.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtzplttswh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihnydfvw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtpnurdmnp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtryytcytw.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtqmdrnufz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtaldoykop.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gttnpaofyh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtcfntkupy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtdhzqhbhy.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtrbdjadjy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtwiafklje.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtqrneopnr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtofmnudif.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtendwaruy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gttnlntmvj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtqfeddinl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvzhavap.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtaysfsyps.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtpodcycfo.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtuznzldbi.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlslcnlsy.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtchckprrg.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtuznyjyho.html


<!-- 参考信息 -->