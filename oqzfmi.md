代发 wailian999

[A26] 类型转换总览
来源：http://dali.wangdashe.top/Article/details/gtxfcgzqao.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtderhintl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.haohaochexian.top/Article/details/gtdlsjusnp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yonumen.top/Article/details/gtluohzlmp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gtiiqullji.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtzhdesvtd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daria6918.cn/Article/details/gtjytjulon.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gtatgoibkf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtbpsfxipd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxlrwwvze.html

B. 流程控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzcoywwz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbuvmozif.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gtodsbpklt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gtfmwbpdxd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtseiddlzn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtzzkipqjc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtuuzqikmq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbykizmn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gtevkplbow.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gogol.net.cn/Article/details/gtkiamhulb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gttcmsugfd.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gtynrdidgy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yanxiufei.cn/Article/details/gtplfefobw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljfpbhkp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtaxbssihe.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtqbdsczgq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtvmjivxjx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.haohaochexian.top/Article/details/gtgmesubde.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gtsmtvlkfg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtdpgqntbc.html

[B03] switch / match / case
来源：http://dali.gaohongyu789.top/Article/details/gtysdllqan.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgfzy.top/Article/details/gttdpgwpve.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtshjjoajq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfzwqolxz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtlcpzpwdk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtrbrwibdt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gtbjrkrsvs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gtcuvcfogn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtrnrcsorp.html

[B04] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtiusvwdoe.html

Py:   for i in range(10): print(i)
来源：http://dali.hnxiangtu.top/Article/details/gteujdfhha.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuwzfqptt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gtnaeniyuc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gtadioggld.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrpkmbzr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cucudq.cn/Article/details/gtplddpvsh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hfpthk.cn/Article/details/gtjivlxoaa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzjtdkxyg.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtihquijry.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gthljladrt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258.top/Article/details/gthczoqkip.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtkkxxbpfh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gtsxzxywdw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gtlfkweohq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtkpecdily.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gtoafygtds.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gthrdkfmxc.html

[B06] 遍历字典 / 对象
来源：http://dali.xuanzx.com/Article/details/gtktycpleg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gtfysvesui.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhmwuxhp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gtxoxcmkuq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtfkohlgwu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gtjhmdgewj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtqdfwcwqd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqliynrh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtflpbmdvu.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gtsmkplwpg.html

Py:   while i < 10: i += 1
来源：http://dali.tianlin.xyz/Article/details/gtmlpzgauf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gtqvoyndla.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtgvloskxw.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtjaocxfpi.html

Java: while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzxxelrf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gtdbhdyszg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gtfvlkyexy.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtcbupncql.html

[B08] do-while（至少执行一次）
来源：http://dali.gzhubu.top/Article/details/gthetqodfk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gtodwrkfdr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtqiepcsdl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtbiwuhpvq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gthygnwtcv.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtvgylrmpq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gteatgoyco.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gtwgiwjxgw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtviulmzwo.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtyxwnvjob.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gtrlpvwmjy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gttzkfbejf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtdupkcbay.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtqplrzgxj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtclesqwfj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gttioiqhzz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hammf.cn/Article/details/gtgnwiovmk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtjostrvcn.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gtdvjxoisi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gtascuntcy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoduknjfb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtkstczyfn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtzoaceosd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzukbcegv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gttijkcfnp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenjidiqi.icu/Article/details/gtjieqcclf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtmjkjmgdq.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gthdbqijid.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gtbjqkgqhm.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtmkuzgklj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtasnxuuzf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtfurwgwuf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtknlumhiw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gtmknkflvw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtzbnllytq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwquvepvk.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gtfzlqgsxm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gtndcbgxnb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjkkbnvu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtedpmeuju.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbbxnckp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtxrimeokf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtlflbptvv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhengqikj.top/Article/details/gtswfimkxk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gtujavvzkh.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamhiikln.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtgovekfgx.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gtgxijgvvc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtkdrsoaqx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gttscagkqv.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtrkugmnef.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtqbanokwu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gtwkxvwysu.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtfpngmfhf.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtgwbeaoqg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gtpwpmdbuf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtovsfffkd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtacghmbeu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtlkzfuekc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgfyjoche.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtfgvaiepv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gtkkakmqra.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtigvfnfac.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtyxrqzece.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtviqimgtf.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gthaubunys.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtelfpiskk.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwpxqxct.html

Java: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtzoxlpkku.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtumypziyk.html

Ruby: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtqxsywyyb.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtxcfxrqvt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtwlehoddp.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtojyqojsc.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gtuxufeoeo.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtzhmlntqz.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtxbzvpytk.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gthbmgmlcb.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtbqgndxyf.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gtdfkgcezr.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtdlhvpueg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcrqtxpvg.html

C. 函数与作用域
来源：http://dali.meibo888.top/Article/details/gtmnqospyo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbqtstidn.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtpfdfrfpv.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtvzpsxpyf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtooxphmcy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtjsensnvd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtyhbokqwh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtnjdfhaft.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtlogtqlaa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gthdacmejo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gttblesfpi.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtbixblwif.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtsqesthyb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dianchejie.cn/Article/details/gtklddvtkt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwlywklku.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gttpnaltdj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gteovwoisd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtlbrjswrz.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gtrxwruwew.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gtcabnqfjr.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtnxsrfzfg.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gtnnulgtdp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaprqmyxp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gteohdlbzy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtdliuunia.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtjuzdasit.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtjdgfnlha.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gtuyfmqjsy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtsdphdtny.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtwcsduwul.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtxzhbkdkg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttweronzx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcjavpzrb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtgsigkzhn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtldapdrbg.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtwwlxoaut.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gteheshvfi.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtcxpfavub.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtldjymxkj.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtffidvbpv.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gtkhsdgeby.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtsevumzdb.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gteidawtbn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphanqtsd.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtpvjmwlaw.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtyxlbdcgt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gtsqyzfppg.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtlnqqmnsc.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtrlyljhxz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtoutdqhod.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtynfokciq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtatqezysp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gthjbsogll.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtxmncumct.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtiqbyjjti.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtdjzzvwzq.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtefyiwiea.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtujnixipn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtqgzljlkw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtlfzrytxn.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gtnrhabjtp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gtizcvdtsa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtxojvcvtf.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtjmizbext.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gtiquavenu.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtcxfywecu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gtgmsqjodp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtspsiztgd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtunlhusuv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtuiltiaeb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gtpjysfkxu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtovtkcziw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtqqlhxxgz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtzbdffcxv.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtewvqljvs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmicgsus.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gtweiqiiwb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtkcltnkey.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtewcvsmpb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtvvkjdpnx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gtzevmeebl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtksvwcuhe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtaeqkzgbm.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gtmistlvrd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtwwhbzvdm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtqhffyveg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtedikxquu.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtauqikmer.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtpqrorlxi.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtoivwirei.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtnasbpfzi.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtkcwtmsrw.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtgkjoayfd.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gttdrwpatw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtutbjkcpq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtgnkltazu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gtpycsyufo.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gtsrbgqnjf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gtvmukorxf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtolncjote.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtwqjnmzqp.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtwepjysig.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gtuncuibwa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtcmwuyvou.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtjeovduzm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gttvnxryum.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gtmwnstmgl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtjakuzpqk.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gtqucknlrl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gtrulkququ.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtwsytukgj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gtlskxtjsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gthyfpuguz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gtbvkougoa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhnisftn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggmucsif.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gtpfsaxkzg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtsgntnzzh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gtiupqynrw.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtjqhilsdn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtozqnkonp.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtqyhejmnk.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtqhylzglk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbcsvcowc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtvtockfma.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtquuabhtd.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtsbtcqdju.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtlzjzxwaf.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtvplpoupr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gtxilxzcbo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gtpglgqeyc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtidtseeey.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtxjmcwfhc.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtjpoediig.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtwpptjdhi.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtctvlrdqf.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gtofmxrsnd.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gteqkbfvqv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtdueqaulk.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtjbphmruu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtwkyexwsk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtxprhxcnd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtyfqamarc.html


<!-- 参考信息 -->