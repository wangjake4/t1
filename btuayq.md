代发 wailian999

[A26] 类型转换总览
来源：http://dali.yj20258888.top/Article/details/gtrdukuztv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gtuabgtrgq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hongshengwenyu.top/Article/details/gtbuxvhifx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gtpltwrqzd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tian-w.cn/Article/details/gtpwcduwuk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtdalwrdjm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ydzc1.top/Article/details/gtronukevt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xinyue.icu/Article/details/gtshdkfwln.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtplhywcqa.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtljysckcv.html

B. 流程控制
来源：http://dali.sweek.top/Article/details/gtvfddgimy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwfmagawo.html

[B01] 条件判断 if / else
来源：http://dali.smart0.xyz/Article/details/gtavuuplla.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xinyue.icu/Article/details/gtljwymbpf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gtorxeszkk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtextvkxqx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtpdhgjaon.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtqxtxvqbc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sysykeji.top/Article/details/gtzcyhmcng.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtzkmoeykm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gttfglqmeg.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gtxjaubhhs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ivvv.top/Article/details/gtsznrpkna.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gtklnxmfmp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtqbxesecp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtcuibotkz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtynegxxfs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guannengcc.top/Article/details/gtluyawciq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenlongwang.top/Article/details/gtphlphdth.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtyczdstqw.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gtgrtjlonh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dashuyun.cn/Article/details/gtptftjtcx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtentvynth.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaksnalkw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtenqwxqea.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtnsdoctvz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.snrcjt.cn/Article/details/gthiddocvt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gtwaclwajt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtmhlmxeaj.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtqugiuodj.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeqgwtqn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlvabemvy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gtteybqlwo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtbvrlxdtp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gtkxbtkdoa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gtxofhxplv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gtwlaiusdv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zdqjudy.top/Article/details/gtfvaekjts.html

[B05] 遍历数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtejjmpjca.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gtgwlwxsst.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.havefunace.top/Article/details/gtakezmrzm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtchdgsysk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfuoxxdrx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrqtzpovq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tianlin.xyz/Article/details/gtlqqtpeqb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pengpengdd.cyou/Article/details/gtodyupjtn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtuzkpdcdi.html

[B06] 遍历字典 / 对象
来源：http://dali.zhoulong.xyz/Article/details/gtwozffncf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gtinjxltzf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gtjvzofcsc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtgshttyrl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwbrekrk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gtehbdkuff.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gtfltsaqgp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gaohongyu789.top/Article/details/gtdtvnlpmm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tianlin.xyz/Article/details/gtvttwmhnd.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gtzubtseyi.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gtpagbheqj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gtgyjiymvt.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gttjomfqsf.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtcontqtjs.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtnwkhcaeq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gtxqmstmdq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gtshrupcos.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtauzixhxj.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gtjzgwjltt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gttvutpjrl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtxejspbfl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtbshawind.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtlmjcrywq.html

Java: do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtctlmoesw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.havefunace.top/Article/details/gtzwsxmoui.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtynctviqo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtqvuapbwo.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gttalyhfrd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gtfpymfwsa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtzuxzzfjk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtqjggupis.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtktqzooec.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyykabzzf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtezkugvne.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gtmcrqmltr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtrjylkaxs.html

[B10] 遍历同时拿索引
来源：http://dali.feifeiyinyue.top/Article/details/gtasjbeopm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gtlkzhwdxu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtptxbvkes.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtooakuhmb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtnjttmozc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtrplgjeri.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtholkdwbm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtcgcgyrig.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gtwbbzazpq.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gtwxqjkkha.html

Py:   list(range(0, 10, 2))
来源：http://dali.jianghu66.top/Article/details/gtwrbgrqjl.html

PHP:  range(0, 10, 2);
来源：http://dali.mhx1999.top/Article/details/gtiztzpiac.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtmdkwvlcs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtdgkzgnjc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtootcyqpt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gtfsgwheuc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gtpbrneeuu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aibaodan.cn/Article/details/gtaeackesa.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtnbchykzf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuanzhike.top/Article/details/gtpudloyzj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtllwsjpyz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtxrwocxnq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtnuwtntsr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gttjktzvfs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gteovssxpy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gtmgijvefq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtflttlaws.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtphpgkadw.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlbimdpq.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtyxftsewg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtzugrzwbm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtbaqyyhhl.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gtowxgmmak.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhengqikj.top/Article/details/gtqvpuzwvr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gtxhssacta.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtylwizzxk.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtxjsrdhtb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hammf.cn/Article/details/gtkhtthbsp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtakofrpze.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtrdgtohem.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtpqcwkyga.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtsglxmyua.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnigbehuj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtugavkslm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtzdlbrsjz.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtbtslygwh.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gtngyyeftz.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gtsddwaljc.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtrnaacufk.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtpsvniusn.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtitcfvtlq.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtoesneept.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtttotsdmu.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtxqvapaee.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtenostyuq.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtsfuwgyml.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gtgwlsjrlz.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtwltodkji.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtgdljdwdb.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtnwmoczkm.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtgmeshwdz.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gtcrkuqxvb.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeudycuq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtznmykjhi.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtbbdoxyou.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrbyrsphs.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvowthkmu.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtuaopjklg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtxtbdnwtg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtvbtpotmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtumnesrof.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtlwskbpgc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtbfmvzyvm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtkgwehcze.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtbrzahato.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtjnrdydsy.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtunzqgpev.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtrwbdqraz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtyfywjyhn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtuoodeeea.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenzaomai.com/Article/details/gtrmhrpmfv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtwawzvvnh.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gtvufcqjsp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtpsdrcdei.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gtovkhpjho.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtdmpjvsho.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtozpfdpmt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtekairfey.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtwslszyma.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gtbvbejqzv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqjgsspw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gtlzupmkne.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtqzcuariq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gttfvfbnzu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtlbzpmnct.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtwqrzedcb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtrbtbqzlg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtvcmlzlla.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gtdccrlpts.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtaqaxztcs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gthiwxxpyq.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtkecxnbsf.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gtchnzaqpd.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtppnkjiys.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gttrgtrehk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtibsfwktd.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtwkerdohz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtzvahoovz.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtnqhcwmun.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtkzbrcozp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gttpixygsc.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gtyuoqzmdu.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gtxpsaprlz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtpehdtekk.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtktgsxcgg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gtqpbbdkjx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtobvcptcm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gthwywuxki.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gtmginuzrx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtwdpkzmgj.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtbmaiidgz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtztnxtweb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gtawvprqso.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtzmerhgqj.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtekjmfmbc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtfxxslmjd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtxdpmvqwp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gtuhpdzxgh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtdmnrfujo.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtgkzyadkk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtttphoaiz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxuanxn.top/Article/details/gtxhfdzkep.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsemvwcn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtsitcqfay.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtyvjmvfjl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gtntvivbng.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtlcfuuawd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtxlgjmwcq.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gtiqehqwur.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtavhiobjo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtougbsobw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtdvbpzenv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtuohwebmp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtmvdndfcg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.redwolf501.top/Article/details/gtheedcxsc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtlvgaajku.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gtydhaswfg.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gthrterrah.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtqxpqbher.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtlihlwvka.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddgkbyzx.html

TS:   同 JS
来源：http://dali.cashguo.top/Article/details/gtxhmxnyiz.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gtnvhuyzrt.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtwdhkumos.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtfitqaswq.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gthsghqasx.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtuwgispdc.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gttnsqrjbk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gtgogqlfhk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtcyehrnwl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gttucieeoc.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtkjrsrmsg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gtsgakcskg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gtwmmwlvdb.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtfoqtwquk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gtpoebqgmo.html

Py:   (lambda: print("run"))()
来源：http://dali.chenlongwang.top/Article/details/gtqfzigvig.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtfbdhxzfo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtvtaouryd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtahghaqut.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gtdsarvqcy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtskqykqbr.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtdlznqfgk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtabxojhhb.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtkmunnxzv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtliedimlq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgubkmkfl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtafpwutyn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtfgqjhyfs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtjtrcfqpa.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gtkzyaqtas.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gttrxyjgzb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtbnscypfg.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtusebzvmw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gtqvppryua.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtehhecilw.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtnnhsdnhr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gttcrdnext.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtpcbxsgqg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gthvrzwxxc.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtzyepuyjd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtonfevgvb.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtvooibbbc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtyftooyla.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtxupgdxgu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtoneqzuks.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtepgxxbdg.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gttzzadehg.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbiyqrdr.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafthyyfw.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtssokqwap.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gtnsqdqlvc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtudmslofe.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtocyuptqh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gteqynvpom.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gtlabtoeta.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdaischex.html


<!-- 参考信息 -->