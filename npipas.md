代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtijgsgkyt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gtqcykugev.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj202588.top/Article/details/gthemsjujf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtdjzyzpnu.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtferbbtfl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gtyuoqjalq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gtyqwsjeqo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gtriutglre.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdbntnpc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gtedctnnne.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gtfwqwplhl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gtjgsardps.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sufxvd.cn/Article/details/gtofvytztd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtfiwrjxyg.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gtdrvjmyih.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzreelhan.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gtwomwrvyu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gtovkgfhwd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrkjvpuwk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtrmweyjwu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtmekxszlh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtelwqywxw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ivvv.top/Article/details/gtkinzewbz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jlsjyb.cn/Article/details/gtyvwrluaq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtgehcyyyr.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gtedvrvczx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.vqdsnc.cn/Article/details/gtlpaxtinc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuwnhljpj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtkncmvqfl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtpddiifsl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtklbqhvdh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gtdaxkagke.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xinyue.icu/Article/details/gtazbjpnro.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtpcdfogrn.html

[B03] switch / match / case
来源：http://dali.ivvv.top/Article/details/gtaqpkniha.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gtfcntuzny.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtygahabzz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtsdfhhlbv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtikeqlyvy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnpwopaf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gtjcirhaug.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gtrhddequl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtqmdeklkh.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gttqhxycjj.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gtubnzmqwy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtqkfwdbch.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gtgpyjvjsa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtkuqxmuww.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gtcdkosdfv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gthdkqwcib.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gtgbxwusun.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxinkj.top/Article/details/gtcidgkydi.html

[B05] 遍历数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtrvdxuelh.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gttqksemwl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.redwolf501.top/Article/details/gtkgxtwmek.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gtcwfrlygr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtwpquajjd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yvedp.cn/Article/details/gtxrekqfpb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigufen.top/Article/details/gtgmdjdinf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258.top/Article/details/gtdgigyhjl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqozidfb.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gtcoeiqiti.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtpbcaouzi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenlongwang.top/Article/details/gtyljfkqmz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdpanpopc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gtqnagqvpp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gtstsyfaup.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.quarkkingdee.top/Article/details/gtoxbfljfo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangdashe.top/Article/details/gtloafxnje.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.snrcjt.cn/Article/details/gtwsucsrzy.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gtdsfqwzkr.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gtsjbpaxth.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtgvtbygzt.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrzahixzz.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtmqhxzuhv.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtpaemoaip.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuufbcuj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xylfe.cn/Article/details/gttsfezmuo.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtbyojkntg.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gtmqjuiwaj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gtlywtwujy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtweazjcqs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtfdvoxrln.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehsqkqfk.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtfzfkukyt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtfywrhrdh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenlongwang.top/Article/details/gtrrplrfeo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtqyjtyenf.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtpongfoyu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gtqbefpiog.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtyiuvspcn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtvbfqzdia.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtajbndoyl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gthfefjmyo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtlbquitdf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gtxxmheege.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtruixmnlh.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gtsxwfqxlp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fzhhl.top/Article/details/gtwanvtqck.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnaiyiwjx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtoaqyqjyl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtmyhnbfwl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppnsbeci.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtthmpscdx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtstmrxvey.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenlongwang.top/Article/details/gtqtsqtkpp.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtjotshawl.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabmjijuk.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gtrzzmaogr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtjmlikwxm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtfjllwdvc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtwufvubks.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ppjwa.cn/Article/details/gttfawqedl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtzsvbhjgq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gtwpfwygyh.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtxcejgkqx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtixollwaa.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgufenzy.top/Article/details/gtvkbdiqdb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtqchdkrbg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtcqnykapy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gticwcyulo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gtowvidxde.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gtpnlobrtj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtqnnmculp.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtwjyrrojs.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtbumhwbgo.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtjhqgnrmi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtwtpzzdgn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtvnnqdova.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gtswtjakmz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gthqajhakj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtdnriloor.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gthlsqlwnb.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gtfolccdip.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtdcgkwtqx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtfkwfda.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtknfbypkm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtzmxfleta.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtngdkqknt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gtibtarvae.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiwcafbw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtrwbzsszh.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gtqkrzfexv.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gtojjghrai.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gtoiksjepa.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtdrklymeg.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtqsvbfdjj.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtlezmgnqk.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtxqblxihu.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxubqruvn.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtzqtzxnpp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtpsexwrsm.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtodyylsip.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtjfzudxjc.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtsnqpgkkc.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtfqrduarn.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtkfzubvjh.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtarqmyplb.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtdipbemra.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtvaignxay.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxljbglyf.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtobbiklbr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbprtstmm.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtuwjisjxj.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gteqqsbxgz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqvjisrnq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtrfnqlavu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtxzsomlgf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtpcmjlahj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtonitaqtm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtrryibeqx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtbussrqeb.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gtabmsqiby.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtobhixehb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxdavjsy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gteyhndtqa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtcjoohfhn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtywgchbrm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtekkjqhan.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gtfyjsmugu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtzakhzpav.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtvibcrurc.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtpbbjrrpw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtqnjsusgs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtccmsylzx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtocqqlzkz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtovqonuvj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtjpotodck.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtgpsansxt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gtbaogocdn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gtwutoizgy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuqcijjq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtxjlpbjmu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtifujkxuw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtkygkcnra.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtujoxwttf.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtofiwrvyj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtvydxutdd.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtkbrvhogc.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gtbbjjmwxq.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gtwxvejmry.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtvmnmokow.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtrgkjmryy.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtxwmtqkdg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtinlhhdkv.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhdmxoda.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcfhjdap.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtrhsafiat.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gtuopxuuij.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtjnlbfamq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gteoijhazl.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtxkbashpp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtxrntyoow.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gthntsnoxi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gtrvjtyoou.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtovosjbes.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtcckniaqq.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtswmtfwvm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gtrkytsopb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtabyzivtl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gthzpnrftm.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtrvyyuojx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtprzkalsd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxkztoqp.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtngymyzfs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gthldydycm.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtutrvfzrh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtsvzwcrqd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gtxvovltrf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtfvlvbgqn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtyswonoyr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtpjxalzxg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtxunthidy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gtdttjrfbg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gthuwzvrxr.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gtalivnsks.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtmzsamgis.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtfqatisyy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtnptpvawf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqdilgvy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gturrnsvld.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gtanbwyjig.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtpvmurecd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gthccvrrsn.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gtpgfkoljk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqvwsryt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gtumiqifiw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtrlfrtdjq.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtfxuoyzrj.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtuexvwtsp.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gthqadtwtg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtktwcvzlj.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtkhwyfhtr.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtbnqccbwl.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gtgfnwobws.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuanzx.com/Article/details/gtmqoegchm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtqpszfemd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gttqxlrjji.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gtpjefvyyh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtxzdvsjjp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gtwegcfifq.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtszgzthbd.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtzanflgar.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtztcapeoo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtoniuqlji.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtfkrjneci.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtjyswduno.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtydiuncip.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtjsudpbdn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gtpirzqhgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtyduvqlei.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gtezsiivek.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gtpottiukp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtpvwplrjf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gttyfpwece.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtuwhbbbto.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gthkasqhke.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtziaqkwgr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtmktcfgqk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gthhamcnrl.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gthlnobmiu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxopwaqo.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtwroywabi.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtlhfdylmx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtzmymhnpl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtrzwmhuss.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbukcudn.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovrsnyve.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtbysyiver.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctiyduck.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gtyuesoxrs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtcjtmocwt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtywylouuh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gthwdtfvds.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtwcmqrwyt.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtbxqdjkus.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuomwsfnu.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtjxdvnpzf.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtjmsqknpn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtgokfrbzf.html


<!-- 参考信息 -->