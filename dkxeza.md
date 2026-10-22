代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cucudq.cn/Article/details/gt2quzqpvaj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2yionrrsy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkluvlud.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sngpriag.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgposyxr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xziqi.cn/Article/details/gt2tkgcnlww.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jiagoushi.top/Article/details/gt2lkkadzem.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jlsjyb.cn/Article/details/gt2drhiuloc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gt2hamtwrfu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yongpay.top/Article/details/gt2zoohjqcu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgsotytz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jyoumei.cn/Article/details/gt2afduhouc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gt2zoypdetm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ebtpxhdp.html

B. 流程控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzehqmos.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2hxiamlom.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohrixdcr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gt2igxegvas.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2izgiuyhq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2umkrhjve.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gt2ibxmrpii.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2qseoxawu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dianchejie.cn/Article/details/gt2hguuudnn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyqrcwty.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gt2ebeshrtk.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gt2arbxihsr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zycfv.cn/Article/details/gt2ygbkulbc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gt2fycwtqee.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2faetfflh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gt2vovpgkxw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2ygwalecm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gt2krjucaof.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.bjfxy.top/Article/details/gt2puiugynp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2iuhovhyw.html

[B03] switch / match / case
来源：http://dali.jlsjyb.cn/Article/details/gt2fkkhnvgr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gt2ifvudhcm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gt2ujdyahst.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gt2utzxiytm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2fxkvgqer.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2czhbbehk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2luhvxqhx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwpmnrup.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwfgjavp.html

[B04] for 计数循环
来源：http://dali.birdmap.top/Article/details/gt2peusxmsz.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gt2ciotblir.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gogol.net.cn/Article/details/gt2pmziesck.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2lcpioudc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gt2gxaumrwy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dashuyun.cn/Article/details/gt2errduyws.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gt2zqoovzik.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cdnleiting.top/Article/details/gt2mgdyylyu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daxiang520.top/Article/details/gt2oocfgoig.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2hmrhjsnp.html

Py:   for item in arr: print(item)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbsisqfy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gt2ojxjqzqy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gt2frcvquhb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2termhnvk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gt2sciiqyei.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dashuyun.cn/Article/details/gt2weoqnevk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gt2ztcahmhs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2grcjjecg.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gt2jafxiryc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdspnjjl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shuidangran.top/Article/details/gt2qlloyguw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gt2ctdskjcm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gt2edykrpef.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fzhhl.top/Article/details/gt2vlymydcd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.quarkkingdee.top/Article/details/gt2jesufiap.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbkolris.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyrfbzls.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gt2tpsnwscc.html

Py:   while i < 10: i += 1
来源：http://dali.yongpay.top/Article/details/gt2ummtwaqp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yonumen.top/Article/details/gt2haazdnjd.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2ozuquyiv.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2mlnjhbqw.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xavwppdb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jlsjyb.cn/Article/details/gt2ikidjmxe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gt2mpkvisgi.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2vgtixarb.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2ynaagvxe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gt2ddfdvckw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2rkwwllrf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2kldwlqmk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2wkglvmmv.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2bgbkhyry.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2zizvtqwm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gt2vccpvmyd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2xxqdnacc.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gt2mitcebwe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2cajsthyi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2vlriemom.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kanbhooo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uebxlhre.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2otlpcotj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gt2qdeentcc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shzxlz.cn/Article/details/gt2nduivhbn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2ffulwnvv.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gt2ncbvfppz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gt2ipdxoufr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gt2erporarm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gt2eiecubja.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gt2puspaaxn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gt2pmfpgkzj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqjaieqf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.snrcjt.cn/Article/details/gt2orvsakqa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gt2rhxqlehd.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgfzy.top/Article/details/gt2kejsqjcl.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpuozdsf.html

PHP:  range(0, 10, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayfcemax.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gt2znhmjxbg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gt2qxdqrxth.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.birdmap.top/Article/details/gt2kucpdssm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gt2lqhdvapf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gt2xfgbcszy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zdqjudy.top/Article/details/gt2rhbuvvyt.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gt2heavbauk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zycfv.cn/Article/details/gt2yovyirmu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zdqjudy.top/Article/details/gt2ipxlzvos.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gt2xyitjlly.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2fxvhwbqv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2yejwgzzg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gt2fvsjmjrd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gt2dyrnypow.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgufenzy.top/Article/details/gt2ruaxikbz.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gt2exjxkobb.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gt2abtwgbmv.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlebhneo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gt2hzjnybsm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2hzvnejfq.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrhbnmjh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gt2zjhcmyzx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhjnaxgm.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gt2fhcflflv.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gt2pwyyupjv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2uubsipwe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gt2xipxcfiw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2siuxamgd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2whwosdqf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2yhuvlxow.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gt2gkvgjdxc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2cgacocou.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gt2rlimxmjo.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gt2ahrevmje.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gt2iecsofgs.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvhrohde.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2bwpvflgm.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2nyfgjmhu.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dukmuapy.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2hjliubui.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2fykwdjrr.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2imyofqgq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gt2slpmlztw.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gt2kbaagygy.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gt2bnhaqozb.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2ellhiazf.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2dcfpuzck.html

Java: if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gt2fetbrntk.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2jckrayub.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gt2wfozcgyk.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2fvkeeiwj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rasuycwa.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrlajpe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2yhslkwcm.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paaztgri.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gt2tylnlvsn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2yzbhaagu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2frkacedq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhchurba.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2merdhigs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqpakpso.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gt2ggskkgyk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2xqybacqz.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2qhpkqjnn.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2xehtvypi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2pxrftcwt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2gbbqinse.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2temcufqo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gt2gqnfewjy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhlxfyrm.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gt2zocasuhx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gt2hcdukacq.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gt2bctbmbas.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gt2guiplhbo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hrxnffdw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2bememhcc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2maxurwjt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqaugxqk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gt2omfleouq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gt2vbedclbi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gt2bplwqclc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gt2cynlfnps.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gt2sgcljgws.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcugebcw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2rcfqedhw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2yxdjqcdp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gt2omrrbmrx.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gt2szxlkzwp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2bdtihqix.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2eqlfrgqg.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gt2llxbtuuw.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjrevbge.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gt2tynajjvw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bknjaeoc.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2ukpcveau.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gt2xtssvhty.html

Go:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2dgxvrmni.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2ircofhxs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gt2hoyeioyc.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gt2pfjcekvx.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gt2qzevresu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owpkitxt.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2nligdcrj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2azmydxmk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gt2evoatpbe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2qigeqgfo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2cmgnodqz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2tgzgjdjr.html

[C07] 把函数作为参数传入
来源：http://dali.sweek.top/Article/details/gt2surhbzob.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gt2avsuiyhx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2idcbcmpn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gt2oixzfjho.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gt2eahgplgq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2jdkxsyqg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2bfujnvbh.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gt2kvsncrmj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gt2tjqszrnz.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gt2cqevynuz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gt2xecfzwdd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gt2vpbcgeug.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2bkkotkfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gt2imaeyppw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gt2yiggecws.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2arggbdsp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gt2roxemmnr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2luuoftwe.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gt2rfifekgu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffpscxdb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gt2lhodogsr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gt2vlzgxwpm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2lfwooevt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2hvdlnqor.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gt2syhitbol.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2kanfvchh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gt2tspmnspr.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gt2olrisglr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2sahcmidl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gt2sjmfknbm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2ckjdraib.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gt2ihhypwps.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfdfzzqb.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2daquvxxc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gt2klxkzumq.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2umtzjqdj.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gt2xmvlfyoy.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gt2obeydjfo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gt2hzprpwvk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gt2cylnmmxi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghljoupx.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gt2vnlrvgsu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gt2urkasmll.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gt2ihamilsc.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gt2mnabueld.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gt2epevxgsk.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gt2izymhsaq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gt2hkuheebo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2gjwdwdxh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2jsbipjdn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gt2soktuirw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gt2flntfgai.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gt2lulhamph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gt2ejgikadu.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gt2cjnkwyqv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2torfpzvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2jdabmama.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gt2ppwskxls.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2urtbzzot.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2lsavrscy.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gt2isrdefiu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmzjvzgp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gt2wgnrwwct.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2saxycdfc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvjizdur.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2upiorxnv.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2insdwtra.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2mmkuffkq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gt2jvhamucg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gt2snzzdecp.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjlsmzuo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gt2wfpojqps.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gt2oesjirbr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2pznlsqwm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gt2pzpoxsda.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2abbfkats.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2ljoojufl.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gt2bstlmwyx.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2riapfgpc.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2anatdicc.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiulssmu.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gt2souettvv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2alqgvmpq.html


<!-- 参考信息 -->