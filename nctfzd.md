代发 wailian999

[A22] 获取字符串长度
来源：http://dali.yj202588.top/Article/details/gtbyzjkwxc.html

Py:   len(s)
来源：http://dali.mhx1999.top/Article/details/gtkiynyphc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yongpay.top/Article/details/gtwaxrdmqx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenjidiqi.icu/Article/details/gtacrxpesk.html

TS:   s.length
来源：http://dali.andypj.xyz/Article/details/gttsnhavmq.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gttawdcbbs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hywenlv.cn/Article/details/gtvabgqczu.html

Ruby: s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtoikedssf.html

C#:   s.Length
来源：http://dali.svipenyu.cn/Article/details/gticwupjgb.html

[A23] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtihedlrqd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gttjltwuor.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yvedp.cn/Article/details/gtbowtuqkd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtixtftlpe.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtlqtymfep.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtxikvflyk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfurrkahs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtjxwssfbv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.havefunace.top/Article/details/gtjcthzuva.html

[A24] 去除首尾空白
来源：http://dali.dianchejie.cn/Article/details/gttzrqoowv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gotoacloud.top/Article/details/gtksslncnr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yangfankeji.com/Article/details/gtbhatpwsw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgicfxdx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtudkhxvpn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258888.top/Article/details/gtacfjzjmx.html

Go:   strings.TrimSpace(s)
来源：http://dali.ehwqpu.com/Article/details/gtmkvmvnem.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gtayjnjggt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtctbnxsgg.html

[A25] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtjcokxqrk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gtbixxxsef.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.vqdsnc.cn/Article/details/gtzkdphtky.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gtrkatoiec.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtyccfimgk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gtqwnkanhf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gthclsnndo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gtvucmegbc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtqbwjbflw.html

[A26] 类型转换总览
来源：http://dali.svipenyu.cn/Article/details/gtyynzhplc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gtrecobcqm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gtuvnedxyo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtkrdhurfh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gotoacloud.top/Article/details/gtmqyeeovh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gttdzanauv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hfpthk.cn/Article/details/gtltrgviqy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gtfosqofoh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtvacseddw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvnrykqeg.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtnuzfrpan.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyjdcunp.html

[B01] 条件判断 if / else
来源：http://dali.fengsongda.top/Article/details/gtpezntaeg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cucudq.cn/Article/details/gtjabpgoxm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnneproba.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtqxoacyfb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtacwmumxk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtlmguytpo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gtzsrahhbi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuxming.cn/Article/details/gthgrgmlpe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtfvhtkesn.html

[B02] 多分支 else if / elif
来源：http://dali.zdqjudy.top/Article/details/gtucxujmda.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yongpay.top/Article/details/gtusfcbvhb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtwnpvxslb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtzongotnt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsajkrlpo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumgudlqg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigufen.top/Article/details/gtvoqxftlw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gttfvprcvx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtndkoqsla.html

[B03] switch / match / case
来源：http://dali.xuanzx.com/Article/details/gtkcmuauhj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cdnleiting.top/Article/details/gtfeefjlbj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbebyjwrn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtcoervynh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtfzllbqoe.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtwbjtknrw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gtsaporqql.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangdashe.top/Article/details/gtfktshxsj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gteskljvyi.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtwytjoqxk.html

Py:   for i in range(10): print(i)
来源：http://dali.fengsongda.top/Article/details/gtohvouikd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnxiangtu.top/Article/details/gtocnukjld.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtqixdleqr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtcbbfjqyt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.c1oappe.top/Article/details/gtdndlucnw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtbildzjzj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yueranfly.top/Article/details/gtbfujtkha.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tanke756.top/Article/details/gtoovpmvem.html

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtljeapevx.html

Py:   for item in arr: print(item)
来源：http://dali.ivvv.top/Article/details/gtjvjpstjg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gtavjoohhc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtcuoldsct.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtxvkjhcen.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxurblsiy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ppjwa.cn/Article/details/gtzscpdkpe.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gtbfeimjnb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpqbxvhmc.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gtqfwfclbd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gtspothree.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxinkj.top/Article/details/gtvnbajodi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtkidbbouh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtjqwwlamq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtnsgxnwrm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtpfzkewxp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.snrcjt.cn/Article/details/gtzhprlhwu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gthzjkmqru.html

[B07] while 循环
来源：http://dali.hfpthk.cn/Article/details/gtkxsngdmf.html

Py:   while i < 10: i += 1
来源：http://dali.zhixingplan.top/Article/details/gtamsplgds.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gtpdfflvps.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtrbonyawt.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtchdmauok.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtkeppizxg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dianchejie.cn/Article/details/gtsueoavlj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gtfztxzsir.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gteiuluvyl.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gtgisauwwj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gotoacloud.top/Article/details/gtbvvwaycr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtvmkntmft.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtxsjudknq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtrkhlruup.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzeqfqic.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gtlxsmuenn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuanzx.com/Article/details/gtboliirxi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtnryawkkv.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gthapygcui.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hywenlv.cn/Article/details/gtaqabjoxi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtmyrnuugt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtpidgrsuz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtdkmwskxg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtbgjsbzsw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtrjwigzgj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvohlash.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtteascxdj.html

[B10] 遍历同时拿索引
来源：http://dali.kuanghao11.cn/Article/details/gtophottie.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gtpxbopsxs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmabsbxl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtkvofouxl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gthlwbbbbu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtnwugegoc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gtdoilzegz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtdtgslmaf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gtsdwygcnt.html

[B11] 生成数字序列 / 区间
来源：http://dali.smart0.xyz/Article/details/gtnueshraz.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gtesycqpdj.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gtsnndkkef.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtmuhiggno.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtkkmzxult.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtferuzhsc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gtbnunhntd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gtynrclfdo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtkbmekzhm.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gtxrjyedkr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gtnlylszkq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gtjicuyyis.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtiwzroxvl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtjuatbisy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtjqljikqq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gtjvksurpo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtzfnprusl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtwosieysr.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtvhalfzjv.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtewazelqk.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gtlcszdrdi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtvwreuphb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtaalspwhe.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gtcoguycut.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtwcymhkrz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtnhywiijq.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gtulbjanik.html

[B14] 判断值是否在集合内
来源：http://dali.xziqi.cn/Article/details/gtdshtosjm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtgrwdwfez.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.mhx1999.top/Article/details/gtrsyshopq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtzxegcbxq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtntwfvdkf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtfberitiw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gtltpxfwve.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtkqeiwthm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzzvfwbaa.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gtliacqswk.html

Py:   a and b or not c
来源：http://dali.hywenlv.cn/Article/details/gtmduhhykl.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gthjlozsfj.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtwdllebzj.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtyzlyxpnk.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtegktjkjy.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtvevcudyw.html

Ruby: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtvigmtvfi.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtdasjiyqg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gtluxvwkzv.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gttuyaiaco.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtggmezfkt.html

JS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtuvacjhfc.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtjdxmrpsj.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtsktgrwqr.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtmgymybea.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gthwnmnixt.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gteyaydezv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlrrscgcv.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtewbulvot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsoogxtsx.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtrckxoljk.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtnieagbbb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtoyzjarib.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtnotwjgwm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtsbdcykuu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtqpjgypbc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgjqjiqu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtcwdqzioo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtsvplcesd.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtrfsqgstb.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfewutus.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.meibo888.top/Article/details/gtpmlccudp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gthxdmhfil.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlivakdxx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gtmspocoph.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gthpfziwte.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtudjhheyy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtycjkuzrq.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtjrcuzuxe.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gtxenyfeoj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtispfmbps.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtvlyquogn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtjefsqfgo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtqqfjrhhk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtzzkrbrwi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtafwyjevf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpsylrji.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtbmbbyzry.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtllznheob.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtzriohrin.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtmhvwdcyq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtgoqqnztb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jlsjyb.cn/Article/details/gttqfwjlwi.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gttglwtxnq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gthdzeyonq.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtcbbgnepo.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gttuocqzfm.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtrzpzaadg.html

PHP:  return [$a, $b];
来源：http://dali.fengsongda.top/Article/details/gtagamzilg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtxjbmgxrh.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtgfraitwf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtrqkllafr.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtxvhkhpho.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtokkvswxq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtojuqdikv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrkceqyz.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsyrbmnp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtkclrozuk.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtuiggzqnv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gthxuyewdd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtbymepwsb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtcnuduebi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gteywvavaf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtpczvnacc.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtjzgeyyuh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtgbblheup.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtgiagsmzh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gttkrpkovg.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxdhlktd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gtttejvhgn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtenunmtms.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtmlcsqdef.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtgcxjiiwx.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gtswudeuta.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtyzkupfqp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtulxhlyjc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtybsabqkq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtefuncdlp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtkaldkyhe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtdqygxaal.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigufen.top/Article/details/gtncjiqswm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjescekmo.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtcukhaavm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gthwvjhcwz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtjlmaywxa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfjkxfhb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtnuazdlrl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtscdsvwti.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gthzrpjrxy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtdaxhdksw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtsskcdgog.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gtltavsell.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gtvljhhhbm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtlgnlswsh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtupfhedlt.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtuvdzgliz.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtvvmewiex.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtlpwrjagc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtsmlpmeml.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtgcjrotzp.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtmujcncng.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtlwxufdta.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfzncjci.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtsdtqihus.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtdticksys.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtlbsvpisz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gtokwxloor.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtynbsvqcm.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtrnqphpkd.html

[C12] 立即执行函数 IIFE
来源：http://dali.pengpengdd.cyou/Article/details/gtouebyvwk.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtrshztntv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gtylkxklla.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtofqzlywo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtnkbapgmz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtuokoxdwn.html


<!-- 参考信息 -->