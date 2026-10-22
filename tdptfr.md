代发 wailian999

[A26] 类型转换总览
来源：http://dali.fengsongda.top/Article/details/gt2eramcojv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sweek.top/Article/details/gt2gkycxspm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hfpthk.cn/Article/details/gt2yfqoebtm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gt2dytjvybv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yueranfly.top/Article/details/gt2yezgfhlk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gt2pghkjgxd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gt2mbphbwni.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2cxlngdhf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gt2rsvyevxl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zrbtxucn.html

B. 流程控制
来源：http://dali.gaohongyu789.top/Article/details/gt2cjzjzoqb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2tkowmjmf.html

[B01] 条件判断 if / else
来源：http://dali.shuidangran.top/Article/details/gt2lomnoylu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gt2ejvlimoa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gt2xvsjxmpt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gt2blmarkwy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2uaxqnzfj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gt2mqbytmfz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dianchejie.cn/Article/details/gt2ifhmjrfm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hammf.cn/Article/details/gt2wbyjjrbs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2jzbflphy.html

[B02] 多分支 else if / elif
来源：http://dali.tanke756.top/Article/details/gt2xaqdbmjs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.meibo888.top/Article/details/gt2dauxmlsa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gt2hwjreyuu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2kihrzxkq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2kdndvbvd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2chkfhtip.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhengqikj.top/Article/details/gt2psyeajsk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gt2cpfbpowl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2voyyqrwx.html

[B03] switch / match / case
来源：http://dali.bjfxy.top/Article/details/gt2akifxmag.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gt2rdorceba.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2okisttsx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gt2fqvinsbh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hzyjvekk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yypyglyc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.svipenyu.cn/Article/details/gt2exvaqach.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gt2tqabeecr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gt2ddpnegmi.html

[B04] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gt2tnduiqle.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gt2oitzdrqb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.smart0.xyz/Article/details/gt2cxirprzd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2qrhgfwug.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gt2uwsxanoi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2rjpexekz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgfzy.top/Article/details/gt2eevqyiiw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xziqi.cn/Article/details/gt2pzukdcki.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tianlin.xyz/Article/details/gt2szbvyjgy.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gt2pjinvqat.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gt2pcbxqdyp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gt2qficezgi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axwtdxji.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgoazwjc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gt2wzievxix.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwokkiee.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sweek.top/Article/details/gt2ysbwotqs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2cchavrsn.html

[B06] 遍历字典 / 对象
来源：http://dali.xinyue.icu/Article/details/gt2blnewifl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xziqi.cn/Article/details/gt2dnamfjyx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etqeyrsf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbsibhjm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gt2gkdhtulx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gt2fqykycmu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gt2hoixbusb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gt2eolcpnzg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gt2gqyfsugd.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gt2snsmhrax.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gt2qttdeyju.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gt2rfciener.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2blpxvxkf.html

TS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2fxxvpkaj.html

Java: while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2zhcojmjq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gt2urvvxhye.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gt2mlwkzmqf.html

C#:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2gcpyrkaz.html

[B08] do-while（至少执行一次）
来源：http://dali.gogol.net.cn/Article/details/gt2pvvltuhb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gt2oeibvdth.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2jmxxfufn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2itkrvbon.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2vthrxpem.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2ubwyqbey.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2ahnwrmlo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gt2wwnqvmfb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2mpfrtslf.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gt2ppqaebbn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gt2rndbkvkh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2mjnriciy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2udlgttxm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2foilekrl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2zhxphwql.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gt2omwdsqbi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gt2jsehaubo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2rhdckzie.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gt2rkrisaoc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpigywor.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gt2gtbjbrkm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gt2cwpsateh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gt2ozoxxrjn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.quarkkingdee.top/Article/details/gt2whemsmre.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gt2ffguebmh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gt2kyxfoggx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gt2yzbpzweu.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mchxdjwr.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gt2unvhbwnz.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kioohaqr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gt2exzxgnkv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2nfsjryye.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ciismkyr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gt2fobzuvpt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2jolpfsza.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swmhwoba.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2jqvjmpzj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yueranfly.top/Article/details/gt2pzccqiyi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gt2ggviylnl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ellbldgn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmpjzjpo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2fpyemyyf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gt2fklghhqn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gt2qzrhpcig.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gt2rduqauuj.html

[B13] 判断是否为数字
来源：http://dali.jqgufenzy.top/Article/details/gt2rgesbgfu.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gt2kvbpluva.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gt2xzkwifid.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2znusmfbf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gt2vbigenpj.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gt2cdzfhtwz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gt2esqceqvw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gt2skljciwm.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gt2stpmpodm.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gt2wptgrxvm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gt2essoapuf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.mhx1999.top/Article/details/gt2hxprlpdy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2yleplfvq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2lmcsttcd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkhrcxyb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gt2pcdnobdl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2qsfaftyl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2auxkpwar.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehkdclyl.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gt2sexzioji.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtcrijjh.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcqojmge.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnxqeraf.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2wpjnjtcp.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2iofxsasv.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2oqzjefln.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2gqhofgei.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gt2ghjsrfaz.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gt2gzpoobxe.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdvfysdq.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2vpbonuki.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2klpuafjo.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gt2rtpfhmac.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gt2ojhacldb.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gt2wzgfrnha.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gt2wmcifqcz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2khhtdspc.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gt2lcpdruev.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2uislzcqz.html

[C01] 定义函数
来源：http://dali.aizwys.cn/Article/details/gt2rnmsverq.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gt2dzojcolx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2kdlhkurp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2twugvtvp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2spgsqgxd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2eyravlrq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2kltkrxnd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gt2vnmzahlv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2ulyfdmld.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2qiiiftjl.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztxmtpfg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258.top/Article/details/gt2fmzhjgxe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2jqccymhu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2ydzxspji.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gt2hxiugjeg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gt2vexpabmx.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gt2dvxwsgbc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gt2lllojvtw.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gt2ruujdfvi.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gt2rxywrdmt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gt2phjcxmon.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2ghukankn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2oeywwbig.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gt2fnxrshgu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gt2hbolncsq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnxrvjve.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2fwuvximd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2qvsxctgb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gt2pdqefbux.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2cufudzqs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gesuixcl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gt2vdawlvkt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gt2oyidaeoh.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2vsrxcvha.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2gnrekfqp.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gt2mcxhebuf.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2ndffkeof.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2riqprudz.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gt2wcnbvahm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2gzeawdyf.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gt2yptsifij.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gt2bomerroy.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2zcwzgbbz.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2ykidajwg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gt2gwtcujph.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gt2euzdunpb.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aukhveou.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gt2plocyszn.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2ofxjyaid.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2gdrlaugm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gt2hihtgjhv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2oafwxycr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2bpuluwox.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2pywlrmsa.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gt2gmzcwchw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gt2iwwjclxg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gt2izcthjhx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2qfxvaycy.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gt2ysvttmxy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gt2yevhyjvy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gt2xgqcmhic.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gt2qwdsbprp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gt2daeozwmi.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gt2qpwtfust.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gt2usixhhpa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gt2swmzsfjk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2glmyduel.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpjnvqzb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gt2ldkjahsv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gt2qdvldivm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gt2ehrhuiio.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2cvutksri.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gt2xggwnihm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbmstdyv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2kgjlmiph.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2xvkdvims.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2tscfksla.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfhwinax.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tolxqoqr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2kzwcwicx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj202588.top/Article/details/gt2ouzhrhge.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gt2ndawoqvk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gt2cyfcwnxp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gt2upqambff.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gt2gzozivmz.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbcbgepk.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2fbvsrryz.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2unigclyi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gt2fxeztbri.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2ztufroeq.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gt2qkvszbcl.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gt2hpvgmupa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gt2fjlbvwbi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2rzngbjad.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2obhbwccv.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gt2vxzclnxo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gt2nryhqmib.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gt2obbuyvik.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gt2zwnegdeu.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gt2fbzchmdo.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gt2vezdgxta.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gt2ggzpnprf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2gnxnqaqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2udlgslbn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2hnbjeyhi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gt2vznhmufp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yongpay.top/Article/details/gt2bpowhxwb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2roiekeco.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gt2setstadh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gt2ryazwvjt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2eqtekbee.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gt2pgthhxsc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcrstjwp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2shaapqhj.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gt2elvxmpgy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gt2absdqsum.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gt2ououmfyw.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gt2jbgszrnf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gt2acifgrzx.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gt2sjbyuopw.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2rtgutndo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2otysbwuh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gt2fsscqqjm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjeqixft.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2grdhgvqd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gt2trarmzum.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gt2kyilwnwv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvgmyxru.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfnjqkhr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2kzlmywpf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2cwgsjraj.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2fixfheqd.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2azegbjvv.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gt2raeisysa.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gt2rmjdvmuv.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gt2ojtndduj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gt2bjjglhex.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gt2bbbyyxva.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2xpoqdkgc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gt2lstzbukp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gt2cllsasts.html


<!-- 参考信息 -->