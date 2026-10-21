代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtsaamyrun.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gthpzprabr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.bjfxy.top/Article/details/gtdahcxxbr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtillcyyrt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtvonpnfbt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ppjwa.cn/Article/details/gtvkpcxysf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sysykeji.top/Article/details/gtqcdbovoe.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daxiang520.top/Article/details/gtwqcaepqs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtsxixugvv.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gthvwzpqhf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtdctenqmg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gthsdzqnyu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtaonrfyya.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtndyxlmic.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnpfetxzh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gzhubu.top/Article/details/gtqitaxvju.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gtmikfqeii.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gtkkkarpuq.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gtsgcmrond.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258888.top/Article/details/gtwnugcnfz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtldaotfvv.html

JS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtnxaomgxe.html

TS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtpgjmglii.html

Java: while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtykxxrwkw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gtocwelxxl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gtgyailoqc.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtwuohtgml.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtlctyboyg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.kuanghao11.cn/Article/details/gtnzvbotbh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtkihcekru.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtcxbluegt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gttdoimgxd.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtmkikuptw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtliezvmgs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtsmpwcbvl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtfwjgxqgc.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmnidlmn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hywenlv.cn/Article/details/gtezinlsjp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtjfcbuwax.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtbxpsaldz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtnyovyucz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtbdxounkr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtzazbiekq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gtzvlrxrxe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtyzsyetpg.html

[B10] 遍历同时拿索引
来源：http://dali.kuanghao11.cn/Article/details/gtzdldqtbo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtazlfuqau.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoldjkav.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtdhsuaoiw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtusdhizgc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtlnxgwxtl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtkltuyyiw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtgwcmwprb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gttmljmkcv.html

[B11] 生成数字序列 / 区间
来源：http://dali.316326.xyz/Article/details/gtlpcfhxpq.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtjojybheb.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtxtcytkod.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtqfdswlit.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtosczjnxl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtytzkzveh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtdusygpww.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtisszphds.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenzaomai.com/Article/details/gtudwgxiff.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gttydgosgq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtvoeqwboj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtnkamaqlb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtsvevzsne.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtsrhqwikx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtonxyenrq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gtumticmzm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gtwyeujgmk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtvqejtbbc.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcjcafsg.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gtbhhrxule.html

PHP:  is_numeric($x)
来源：http://dali.hammf.cn/Article/details/gthklosjkk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtifedlsat.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjcfsbjc.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gtfeufkjbe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtepmotgvs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtrcykzirq.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gtiexuavkz.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gtrjkkjear.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhiwuduotai.top/Article/details/gthifbllwe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvklogdl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtrfljruit.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtarbvwiys.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtijiyobuy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtamkvumzc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtxztbkqsf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtutkoxlce.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtumurlmss.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gtjgdzaixx.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gtwrhvbuth.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtpliuylrb.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtvtoxhlmd.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtdqjqkwic.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtluotazwq.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtgyfljprv.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtaerxngit.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gtosihxnra.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtumvarpmy.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gthhyfnfod.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtpsjchsdr.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtruihwmsm.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtivgwzcor.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtielttvgk.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtilpivrjf.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtdttbudoj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqjiaosly.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gtljcrklkg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfksjocna.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtgoyyitdo.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gtqwpnxdro.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtmetibonp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjsgirsi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkgoosjc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtntgqeaku.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gthccstjgc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmtsoenj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gttffrxwhd.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpirwjkv.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gthdhpfwnk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtectmewnh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtocpxwsfd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtiraixzly.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gtuhqvhbok.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtmybgdvnk.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtiqydhnee.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtevhxpdvk.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtalkfmpdm.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtlckptsue.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtprorpqvr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtwoutmdjf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnllfnidi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtxfnywkfr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gaohongyu789.top/Article/details/gthqawruyd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtvnulplgo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gtoqgjjmju.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gtlrclxadq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gttiqdqgcs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqjmgpzd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtadzokdla.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtaklwgjju.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtdydjagwv.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtdtmuhpct.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtqfolcpbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtwrklywoa.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gterfymusg.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtiteydpaj.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtalpukdol.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtlvxnrcrl.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtsfxqkpur.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmtkzwvc.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gthxinstjr.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gtgnugdvoh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtarxiovpl.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gtfyyztpxy.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtbjugrhxl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gttwnkkzxu.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtutctiwox.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtroawdpqx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gtspdthodh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtywduhawa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtutewdube.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtjslwvvwu.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtikrepsfw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtsnavbiey.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtlkchiibp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtegheyygf.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtctjaozfl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtnrrhfuww.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gtcgkhzjcg.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gttxafejjk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gtkniwaovr.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtcasitcfl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtkmkafujn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtdfwqkzxk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtsgufefwn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtbcnrggov.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gtmteqepaq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gttgyqcdig.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xziqi.cn/Article/details/gtznoowqhz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtjyolguid.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtigbpiszc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtzoeycznc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtxofbgdbg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtshvgpvnw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtbolyshik.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjsogbpz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gtxklcncyy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gttraetnjh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtvzyzibfl.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gtekamiach.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtvwgaigqp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fengsongda.top/Article/details/gtyvoaiqnr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gticjtpssv.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtmpuxeprd.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtglmrpvrp.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtfpradzpy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtkgkfxtuw.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtvbdtnuow.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtctaemmgz.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtyqsdtysc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gttblmylgj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtdlahyyip.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtlpaqmjso.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtbucdzztd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtoyokosad.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtmhjxkngv.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gtjdtjjbmp.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtqwjutkzt.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtfjsolwhx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.quarkkingdee.top/Article/details/gtnlpsblig.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtsgcjuxdd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgkpxnjs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtobrdssmk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtxdwwzacd.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gtnphwjoco.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuozmvmzb.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtqonzdnxc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtxeudhghp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtsrlgzhzz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gtkczjxvfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtokzkrlpm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtrmzhgtdy.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtftaoulyo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtgsijcxvj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtkinsymsn.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtqskowxou.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtmvbjmqsh.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtjkcblhpe.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtzurkjkou.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiviktsqo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtwlelonlw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtjtrdxdlz.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhacdofl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtdxiwldnq.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtadeifvox.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gttjqaohfl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtdmdppquk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtoxwihkmc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtosxvkded.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gtmvoopiwl.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gthfwxnykq.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gtjnhcucbj.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtcvenoyvd.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gtvwsgwomr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtmbcvvqrn.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtpwomphuh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtfavhgxrx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtstfhraqk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtubmjgdmv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtekywphhr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtscsraphi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtycqlvtyb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtakzudccp.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtnsrmnfei.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqnhtitev.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtnkilismg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtimgaawlu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtaxqzwzfg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtjstdaboq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtsjfcguqd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtrxebqkgi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gtfmijrzkc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtlunbsisp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtjylypofb.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtqrzzefse.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtbyubngrf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtyrqfbaxv.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtuxqahucj.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtoaowwfbg.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqosnsfbt.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gthodszahd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtpibbszlb.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowzdjbbb.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gthgqslahn.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtvyqfgliv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gtvssoiyin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtxktqdxtc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtctgzasip.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtetkndqsj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtukwrzrwe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtksratyvz.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtfnfjddub.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gtoexzyeju.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gtfpcjkwvx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gteojgbofl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtrhluzdsp.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtevzmcgow.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtgauitsca.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gtwrhiccnm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtsqesvacs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtzuusoyol.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtcebarkrf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyjtunjb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gticbswscp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtdvtejlfg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivsorjrh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gthrrbusrm.html


<!-- 参考信息 -->