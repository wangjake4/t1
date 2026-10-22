代发 wailian999

Py:   f"{3.14159:.2f}"
来源：http://dali.yuxming.cn/Article/details/gtowdigiyf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gthbtpkeof.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkivgcnz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtrqpmgbop.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gthroocwkz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtiggolaro.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfazobhpb.html

C#:   3.14159.ToString("F2")
来源：http://dali.vqdsnc.cn/Article/details/gttiorpqju.html

[A22] 获取字符串长度
来源：http://dali.wangdashe.top/Article/details/gthrnvsmgu.html

Py:   len(s)
来源：http://dali.shuidangran.top/Article/details/gtmywfevko.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.andypj.xyz/Article/details/gtgnwbwitt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daxiang520.top/Article/details/gtkzchzyyq.html

TS:   s.length
来源：http://dali.nanxuanxn.top/Article/details/gtcvvvismw.html

Java: s.length()
来源：http://dali.dianchejie.cn/Article/details/gtnobtcqks.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.9152youxi.cn/Article/details/gtnqfguryp.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gteqslqgzp.html

C#:   s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtojcptbea.html

[A23] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtpuphapxm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cdnleiting.top/Article/details/gtvfyzdbhw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.iojbl.cn/Article/details/gtlfjvyuus.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtywpauddc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtrlsaswsk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrovendf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhongyouzk.top/Article/details/gtrosurimh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtgtlsmtic.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yongpay.top/Article/details/gtuqkfbzza.html

[A24] 去除首尾空白
来源：http://dali.zhoulong.xyz/Article/details/gtffbiwuij.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtfjstukgv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.bjfxy.top/Article/details/gtldheitwc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtegjlkyfs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtcdmxtfyv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hysaishi.cn/Article/details/gtglmwuhrj.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gtpsbkopht.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shzxlz.cn/Article/details/gtbqhsmtbe.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtriudvzmr.html

[A25] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtclaozbht.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sufxvd.cn/Article/details/gthtbiwzdw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gtigayoerl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtplecpcaw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtbwyvlerj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtygwltcgm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtwxozmgul.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gtnufqromw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gtrggnrmfp.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gtorfwvfmf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sysykeji.top/Article/details/gtihtumjip.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gtsvoqxyli.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gtsdlohbgb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hammf.cn/Article/details/gtjzskoxnz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtgoyothws.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shzxlz.cn/Article/details/gtsuxtobzm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtnyapvtsp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gttqeoopfx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxshbimys.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gtitvvevte.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvhlftiro.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gtznzyklxo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gaohongyu789.top/Article/details/gteqohlebl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hysaishi.cn/Article/details/gtttdswdnz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtqyqmcnck.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtnnlxjtcl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtndljtrfh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gtxkzchggp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gtwalkbixd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtubtzjocp.html

[B02] 多分支 else if / elif
来源：http://dali.hnqzz.top/Article/details/gtbpbrfkts.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgfzy.top/Article/details/gtqegjcuwz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbwhxcmuj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtbxomnwaz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtellulhwi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtbbwudpqo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yongpay.top/Article/details/gtcpnujmnv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hywenlv.cn/Article/details/gtpbhnleuz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtramhhaeu.html

[B03] switch / match / case
来源：http://dali.nanxinkj.top/Article/details/gtnifuaoev.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hywenlv.cn/Article/details/gtlxskabgw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtlyaajnvv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtzxwozbnu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrbburizk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtrbwkncvj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gtagsjeees.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuanzx.com/Article/details/gtandaaiyn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gtdmewmrus.html

[B04] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtqapnjwna.html

Py:   for i in range(10): print(i)
来源：http://dali.hysaishi.cn/Article/details/gtqugqbxyf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gtimijtbsz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtnhlmtjxg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtyjcxnoux.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gthryuwjfi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhengqikj.top/Article/details/gtexxhikay.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sxryk.cn/Article/details/gtpnzagxri.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hywenlv.cn/Article/details/gtqmgltdgq.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtqeidfkld.html

Py:   for item in arr: print(item)
来源：http://dali.xuanzx.com/Article/details/gtyltyjvco.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xinyue.icu/Article/details/gtowrcotgv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gtlhxxuljl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtenuofrdb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxklhbzkt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.andypj.xyz/Article/details/gtmowqsjoq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuanzhike.top/Article/details/gtfrwcoyeo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gtttcsqbql.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gttngzzdoy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtwdnuuyfn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gtpfkuhbot.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtrvhqxssd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxycvvdy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtprijcwnp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtsjzqbbws.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gzhubu.top/Article/details/gttokbtera.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtkbrtabyf.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtxqlawdoy.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtfzvurrzb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtwhsuyeom.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtsbmcweqx.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtdwuwvphw.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtxulibjsz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtuhiomyuo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xinyue.icu/Article/details/gtrrwgpiqj.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtftcqjjgg.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gtjzsmdesd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtkhrnbqfl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtidiffyks.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtmiavnwsq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtytmjyvnp.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsghtloha.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gtrouhmkgy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gtwudrqykd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaszjmuul.html

[B09] break 与 continue
来源：http://dali.hfpthk.cn/Article/details/gtximglsac.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258.top/Article/details/gtkojevhoy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtlrflgvor.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtsyqcvtgk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpibzdexo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvltjljfy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzveipiqv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtkhmsdhjt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtgvgtzuib.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtjzkswvfh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gtnarxfufq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtaxbjerbv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtvbzanwho.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtcxvirgkv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvkegebp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhofokhv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gtdhdhtdps.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtptxdccoj.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtcnjgtpkf.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gtlebdnhbt.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtgdihxraf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtdlgdyuif.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtxdxwlzzt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtynvtdpso.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtfsftichw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gtapnclzsn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqoiacssr.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gtggjicecl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gttpcclrqi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gtkyubgnrs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtqahfzfpo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtzeaeoyqs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtwfupezvz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtxzmwxlqa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gtobbmtcym.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gtvnawsvzx.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gtmqppxjfe.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gtpsduofuq.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmxurkxv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtaxalvufk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gteghnfvyn.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtywzheagk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtnlgilpue.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gthixoezyi.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtwkpovihf.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gtmuexandl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtkbmixyvu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtxdvanzzz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtfvvoztkg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtauojgtcu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gtrvnwhujj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gtdsycnuwl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtndasvpqi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtxghzirxm.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtdlzgiabe.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gtfmvyhpmp.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejomlykq.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtrkxfghdb.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtdzzdshux.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gttdpscguh.html

Go:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtbiqvtrra.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gthkygoqqw.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtlzbbfefe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtvhgjcajg.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtyaaiamnk.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtserchyzz.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtiwwhgldw.html

TS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtuxppgnxv.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtltvppopq.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtnsttqbhh.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtsngvcmeq.html

C#:   if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtozbdlybc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthfbarzus.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtehymbucb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqjfsqcl.html

[C01] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtiocxognr.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtkzptghsb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbqmybpev.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtabwnrfyw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtnimqgwjm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtjpwoxpwx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtnsnugvbj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtyxhpcjqh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtxtjgszvv.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gttyrrbcab.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gtnzdtidxf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gtozhykhiy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtevsfzwkm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtzpkxhiuo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtrablczww.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtytpfwgxr.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtnympqywi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtkxfvntpu.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtugquxuof.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtylrfouhf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtadlalvuk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtzfmqvwbk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtbbcmkzca.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtgdwyaqmy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtfzzooycv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtomnrnggy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtjeystggc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpkcklxa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtxviqwtsn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gtdybmgxft.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtejfoqcjt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtzwrzzuva.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtovqqhmam.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtwumiazem.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtsqbdutdc.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtaxyabgiu.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtbizepyax.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtwpkbdrrd.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gtusqpdfrg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtuvihqxik.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtdzzusskg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gtlvjpzign.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtkfbcracp.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gtnlmoquac.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gtgkpdogus.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtxmcgbbma.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gtnpkqyicy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtnisfaebu.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtmmusywfz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gthsouaicv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtdkzijzem.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtqiklspct.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gtothxjcvm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtbqmisebf.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtatpgqjvf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtepwoagcz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtxemahklx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gtheguharl.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gthnkpcnba.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gthatgwhna.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtchznzkzo.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidsuecpe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gthpspwgjm.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtsloazjkd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtmhoqxkky.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gttcyospqo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtckghufst.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtpiovfdgc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gtjdzewqqi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtnsabeofi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpalppau.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtxhojcvip.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtrhblztsj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvdhorpo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcflcmasl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtyobexvsp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtajjqhbfw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtrcddejcj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtisxlfjqf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtzijgjihq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtwxskfnrz.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtxqifklxc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtufrivacy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gtcecdzjyr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtdswczxkj.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gtgrfttlgy.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gtyxvrebzl.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gthbjjbdav.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtrmfhawwj.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtfbhuzixk.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gtaplpubkq.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtfsppidrd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtgrskssii.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtagglkrjz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtjkcozuly.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrcyhtjb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gttceiyzws.html


<!-- 参考信息 -->