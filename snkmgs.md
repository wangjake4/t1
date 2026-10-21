代发 wailian999

[A22] 获取字符串长度
来源：http://dali.birdmap.top/Article/details/gtdudimend.html

Py:   len(s)
来源：http://dali.fengsongda.top/Article/details/gtrbbzgmpw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aibaodan.cn/Article/details/gtgkcbkydm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pycfn.com/Article/details/gtjndoypgw.html

TS:   s.length
来源：http://dali.hysaishi.cn/Article/details/gtdpmxxmkz.html

Java: s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqownjvbs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtzqetzzec.html

Ruby: s.length
来源：http://dali.hnxiangtu.top/Article/details/gtzpfdhezd.html

C#:   s.Length
来源：http://dali.tianlin.xyz/Article/details/gtkamfamnr.html

[A23] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtlenrpmnk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangdashe.top/Article/details/gtrpfbsxlx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gtfqdgghoz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtwnyuugse.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtftlaptcx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtacuhdnvn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhengqikj.top/Article/details/gtckypxdxd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gthexwtvxe.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gtdsmlsvgf.html

[A24] 去除首尾空白
来源：http://dali.hywenlv.cn/Article/details/gttgmgwmlw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcedpraru.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gtvqdypyto.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtxphnzgsb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtalrcdhez.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gtuaqfmucf.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgfzy.top/Article/details/gtmwqxwplt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hywenlv.cn/Article/details/gtugrfrejj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmurztucg.html

[A25] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtwwcqttrz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhiwuduotai.top/Article/details/gtavxqrskl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbezfuzqt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtfigqleew.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtuetfonui.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgfzy.top/Article/details/gtzrchjyuy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtytzbjklz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.feifeiyinyue.top/Article/details/gtachqymit.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gtntmofdjj.html

[A26] 类型转换总览
来源：http://dali.chenjidiqi.icu/Article/details/gtlilaimny.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hammf.cn/Article/details/gthbjclzun.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sufxvd.cn/Article/details/gtncyvzbom.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtfauimyzz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuanzx.com/Article/details/gtmslpfboa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtifhpvjws.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.meibo888.top/Article/details/gtmreqnrqs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtdnyrugcc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtdxsaoswb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfslpkajg.html

B. 流程控制
来源：http://dali.yueranfly.top/Article/details/gtxryniwze.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwuttcgdu.html

[B01] 条件判断 if / else
来源：http://dali.sysykeji.top/Article/details/gtgtzyycxr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtmwvgykdo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gtchujibus.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtyvfggqgb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtyqkbaxoq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtckeorouc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aibaodan.cn/Article/details/gtrnprbizx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gtejkqmclr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuuqrbkb.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gtchaaizxs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hongshengwenyu.top/Article/details/gtewbxcped.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.316326.xyz/Article/details/gtitmpnees.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gthjbrbfyo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtyzbdslyf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtzckokalf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dianchejie.cn/Article/details/gtechcvacr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj202588.top/Article/details/gtvyofgqwp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtkaovpyur.html

[B03] switch / match / case
来源：http://dali.yj20258888.top/Article/details/gtvzfpptnj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258888.top/Article/details/gtnnbszeys.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtviluxvek.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtdrvuxsdw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtitqartpj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpkdxjcv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngtgilrv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hywenlv.cn/Article/details/gtmevldqnl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtfjrncigd.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtxyixgnue.html

Py:   for i in range(10): print(i)
来源：http://dali.hnxiangtu.top/Article/details/gtjplxyekb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhongyouzk.top/Article/details/gtktwckaec.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtjgkgdovo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtgemhgubi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gtghbyeesu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangdashe.top/Article/details/gtfbjlljwj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gtyqiwtzwc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gtkjrkrldv.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtyjqwnptc.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtrmzgsvgk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gtqxcjkooy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtijkoyxdm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtumfatbwh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.0kj1m.cn/Article/details/gtkykusnvo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfymgodr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenzaomai.com/Article/details/gtivhzeuro.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhixingplan.top/Article/details/gtflrhdvid.html

[B06] 遍历字典 / 对象
来源：http://dali.xuanzx.com/Article/details/gtkwpsvdxx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gtctzaugnd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtvetamgxa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtrwdexfkt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtipofojao.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoveihgjv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gthqnmcarb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gthbafwyyq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gtisjsjjzc.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gtspjgnpza.html

Py:   while i < 10: i += 1
来源：http://dali.daxiang520.top/Article/details/gtzchvefdl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlcfeevo.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtqrjujjfb.html

TS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtzslwxirc.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtlxnhohjp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.0kj1m.cn/Article/details/gtoavdcycq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkpxahdsv.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtcvacizfo.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtokrrzjph.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gtceerxmsk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtujauulch.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtgwbygwcf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwhbvxzd.html

Java: do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtwdjsrhwl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gtsuostuch.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gtufrprbch.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtdekbsark.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gtnsthftls.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gtbhrevgmy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtkblsosqi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtzvhmubdq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtfodygivx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gttsiqgrvt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtgbvflwmm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtvxtnpfko.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtphtqwthv.html

[B10] 遍历同时拿索引
来源：http://dali.yonumen.top/Article/details/gtyxluoemq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gtbbbxchks.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtpvtyvrgi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtsbsqmddu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gthjzsepnw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtcjscuhup.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtkupfelyg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtvvbnqgbk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtafnxrnis.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gtiwkohhgh.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtfcxzhyld.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gthpmyaldj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtuorhuulx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtslhfceyf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtqbkoxngy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gtdcthhilv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtjudmttpm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gthjloprrc.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gthueenqtr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gtbfdlmjno.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gtnuwffqql.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtnthxrvci.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gttvuboqbw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtrnawewmz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrswxwsxc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gtauzelnae.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shuidangran.top/Article/details/gtvggysqqo.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gthrutaeum.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtrsdrwhmt.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gtmmfkqrsd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtdfctzidi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrghbkfnc.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gtbkkgchop.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gtqxylpstq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gtxsfuwtgr.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtkjqclndz.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtcdwroade.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gotoacloud.top/Article/details/gtdehxyyiy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gtetpjqxmn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtklyatjwf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtnxumcuwi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtvoxcnfny.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtsigrinqr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gtlxexohhr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtqfadqsrh.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqvwhehz.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gtryrgotng.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtfmeehjyu.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmwpoozh.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtikrjaeif.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpggbmme.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigdsshhf.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoimptbon.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtkpuepoor.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gthdujetnr.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtrycxqohq.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcuzvtdrv.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtcdgjowup.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtbcsbqsrc.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtkmlzutas.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtocvqshzu.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gtjkdsodnq.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtjuqimptu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqrpybpxq.html

C. 函数与作用域
来源：http://dali.jyoumei.cn/Article/details/gtkwlsujau.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrdqnhqvc.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtpclptaug.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtscqunbhb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtlbjhusij.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsrbbtqk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gticvyinui.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtsowdjqvu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtftzyxrti.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtxyhpmwzo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gttzaktooj.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtcwqkhpca.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtamixknlf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtddzdlprm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtjhibhaas.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtaqnyrhzc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtksbefsau.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtpgqknmnu.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxffguzh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gtrhwquzxt.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gthpwydjmy.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtnvvrmsel.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtehhugmqc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gthwhorluw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtumwvrcdq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gtbonyjvjy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrawxtkx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtppqyjkja.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtciizbgra.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gthwnwkcff.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtyjjljmzu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtosezpvkw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtdpvxezdk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtiqnkabfu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gttncpdlyk.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gthouobail.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfzdwuyv.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtpuuarugw.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gttjcaegxq.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtbzonkfuj.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gtvjtdfshk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtetyaqvff.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gttffolvhw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gthkncgkdm.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtfuoehrfr.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtumiiyfjm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtqvfjksix.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtmziugrvo.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtpjtanrut.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gtkbmtuews.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtpidjessu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwwpzxzg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtgudlcted.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtknvhamky.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtlmiprtlc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtzvbvrkhz.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtppxhrivp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtcbbjmmfx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtcpsayxwj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gtdjwitwhv.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gtgwjsfifz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gtyuhieots.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gteouidjzv.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtjmrvpqnh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gtfdngdjtk.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtplgebmew.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gtkyslawqu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdurvrdpw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtaamdtmeh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtaxdbbilw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtfoigekgu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtriwcad.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtibtivbhm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtctrsivoh.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtldicsrbw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtqqmicbdl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtdlnekxdo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtuwbrppgq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtsfayjctm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtclshtxhz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtcrxtnsdm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtnignoicn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtrycawkiq.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtmfcneuhu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtgfqyiqts.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnudxwwn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtxysfjsht.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gttikewwgd.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtkaodfhmc.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtamaaqpyg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytcmdfea.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtxvjjvakm.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtrhklqwhj.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gteqqjchdu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gtuxnhlfbl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtzpdwxluj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtayissecq.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gteknzacmi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtrviysfpl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gtseiuexey.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtadqjblkr.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtcggcrlmx.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtaegpvnzi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtjswwypej.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtdtgezrtb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtwfafejcd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtncdqxwyz.html


<!-- 参考信息 -->