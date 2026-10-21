代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuxming.cn/Article/details/gtrtuobvhe.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cheryme.top/Article/details/gtigxlsohl.html

TS:   // Node.js：readline 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbirhkwul.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yueranfly.top/Article/details/gtmgchwpdg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gtxljrltwb.html

Ruby: gets.chomp
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiceptnw.html

C#:   Console.ReadLine();
来源：http://dali.9152youxi.cn/Article/details/gttxtfkaps.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gtjzmlfrtt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jlsjyb.cn/Article/details/gtwsppwvok.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjaaongj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtlnkapgoz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvrouoql.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtuxoqybux.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gtqzpskovw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtzftkubwk.html

C#:   3.14159.ToString("F2")
来源：http://dali.mhx1999.top/Article/details/gtjogfklxn.html

[A22] 获取字符串长度
来源：http://dali.cheryme.top/Article/details/gtmlwwthpw.html

Py:   len(s)
来源：http://dali.hnqzz.top/Article/details/gtszccubvd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gtkvpqvmrl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sufxvd.cn/Article/details/gtpczrfbov.html

TS:   s.length
来源：http://dali.guowangkeji.top/Article/details/gtqhqptecf.html

Java: s.length()
来源：http://dali.0kj1m.cn/Article/details/gtkbwzerxc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ehwqpu.com/Article/details/gthapumhyr.html

Ruby: s.length
来源：http://dali.fzhhl.top/Article/details/gttiwxsyrd.html

C#:   s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtzexxdpxe.html

[A23] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtydtyohao.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xziqi.cn/Article/details/gtlscnsphk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gtbpbwvkqf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtoqykgodi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtfhwzmjjj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtqgkdcsxs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gttxbyrxxh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtcdezttpx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhengqikj.top/Article/details/gtzesgczfg.html

[A24] 去除首尾空白
来源：http://dali.wangdashe.top/Article/details/gtrxjgpano.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sxryk.cn/Article/details/gttbjfgudd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gtehombvuu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtftynxjhs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtqmtcjbzl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangdashe.top/Article/details/gttlyurveq.html

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtbyvcvmsw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenjidiqi.icu/Article/details/gtbmsglbxt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaxmnyjq.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gttofekypx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hongshengwenyu.top/Article/details/gtkvregzpz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gtaxunligx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycyavwho.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtgykhpejx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guannengcc.top/Article/details/gtdrxeisiu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtywftqxee.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.andypj.xyz/Article/details/gtmegofpnz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gtxreqlmda.html

[A26] 类型转换总览
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhpajcmt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gtobjjxptl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gthogbblks.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shangyingyoupin.top/Article/details/gtgxntvabg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.c1oappe.top/Article/details/gtwhyybocu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gttarffgxb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sufxvd.cn/Article/details/gtxxsotltk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtyfevauto.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gtzjxzkpnq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcbbvlkhj.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gtohnfmanj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqlsosbru.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhoahoty.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sysykeji.top/Article/details/gtoqheaamd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gtmxueuarr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtoehvnnaj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtumpzdbmg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtcgjrogpp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigfzy.top/Article/details/gtybeibbil.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenlongwang.top/Article/details/gtwrasutxd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtzqinserd.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtformxyvq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gaohongyu789.top/Article/details/gtqdtfdzpo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xinyue.icu/Article/details/gtxtrasipf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtmtxqyxzq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbzchrcs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtplrnbtoj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gtyjjdynwz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gtbjemsnem.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtskmsvvbg.html

[B03] switch / match / case
来源：http://dali.zhongyouzk.top/Article/details/gtbubrlmop.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hammf.cn/Article/details/gtxgniuobp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtlenognfn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtpgyywhtx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtofbmeexk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtlrvspwms.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtpglhorzi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gttcyqwwxr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hammf.cn/Article/details/gtkorbrndz.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtjwaelnzu.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gtqyewfdkg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yongpay.top/Article/details/gtbbougsau.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtrfmmrnip.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtuowmmbru.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcxzqgei.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gaohongyu789.top/Article/details/gtzxlfleis.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gtxiuzrkna.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtqlozarnx.html

[B05] 遍历数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtpfdhvuge.html

Py:   for item in arr: print(item)
来源：http://dali.guannengcc.top/Article/details/gtdzlrtaay.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpalncpvs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtszutcpfo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gtobnbpxyr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbhxjemff.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtfdxgkcpy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtfbqyouvx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.smart0.xyz/Article/details/gtgcaqcyod.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gtlebboljc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gtrrwxlqsk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtfeohmxbt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtiefyjycj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gtyuudoloa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkfnvbrhh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aibaodan.cn/Article/details/gtqkzwddno.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtwtlujshb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtvxseovmk.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtzmiyvlpc.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gtsdaspgvt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnqzz.top/Article/details/gtecyksxwb.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtjjkekfqr.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtsweisyoe.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtfbkllvvh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gtegckxsnh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gtkasycgco.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtxsszwxxm.html

[B08] do-while（至少执行一次）
来源：http://dali.fzhhl.top/Article/details/gtynfmxqlw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aizwys.cn/Article/details/gtbpyxyoaf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gttgmxnznu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gteimhatgs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtatcqopzc.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtifddhakn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtlnlfqhfk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtjittijte.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtjswotnec.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gtpvlrgzgp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gtzqptwluv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtfpybqgsr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtrogxnulc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmpbwxwg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphcvheov.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtdnpdvkwv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtrkdegtjb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtrsvvlplr.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtbrzvjyqx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gtrlawuupn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gtyzbrulvb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfaqxjpk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtfofyxdpd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gtnjefwvim.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258888.top/Article/details/gtifennomd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gtlgmbquul.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtppvwqwdy.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtjglakcwc.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gtyxeedjat.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtdpuebxpf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtwmdhsnzm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtnnfwlpcj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxkhlmra.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gtobdvqflj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtyzrvrqnz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtkaemgthz.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gtsyqzzknw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtzxkfthcc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtuvxlcjip.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtfsqptrny.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtuezusfsw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtaelzhmpc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gtczchmlli.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gtsdsgdsag.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ppjwa.cn/Article/details/gtejpzfazl.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtodvcobog.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtwnaekdsn.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtstjypdkq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtyaawdyun.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtgcqiamuu.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gtogvctwyp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gtuvkpwepo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxuanxn.top/Article/details/gtcvjzsvah.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtlqiivmtw.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gtqbnmcidu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gtrgfnflgj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtnxewmeag.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtqorqxefi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtgydejngj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gzhubu.top/Article/details/gtwecngwjq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gtesaprmnt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtngiznryj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtrcatujfd.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtdsooswxm.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gtkthkoyyx.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtfyzvocsg.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gthftprbga.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtxfhwddap.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawnvkukd.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtziudufsk.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gttgwviqxz.html

C#:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtskzjseko.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtavumpdqi.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtqzcfxamu.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtpdkyaydu.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtwslirolo.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtewniemjs.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtewsoxeuv.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gtaiultise.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gteqflzxpi.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqnzvqlg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtejxvfxsk.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtzvmqglyd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfrlcutdb.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtalauywhc.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gthpwfgmoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtzmqbxpyq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtwvsbwggb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtbopjisvr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtsejjlyjy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtaqmarepj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtrjeizlrg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtaesbctwr.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtxtqdlwam.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtkqgblphc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtyhiayiob.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtlhkvjkdg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtxoguhqiu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gtftvvrkjm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtlbjhdyis.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtgwzlqumr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gtfcwqikkc.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtntcpkzxa.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gtytovariy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gttbjhdtne.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpkhffwko.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxzudvgq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtxmocfnuk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtjmyfrgyx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtahhggepr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gtryavgqtw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtghzptabz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwbrcwuh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtlwtqobyv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtxzldcfnt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtpdrbeycc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtxkhxemwd.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtpvcpzxst.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtunjodrtx.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtyhcblzgq.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtjbhkcppj.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtxjefvlkn.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtralesboa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtlvouikyx.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtouopcevo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gtxjxjaooh.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtgpmayhqq.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtzhpaikes.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtzdrugqex.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gtdqycmacb.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtzxssikzw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtacvkjstg.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtjxgjdsum.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gtyplksxkf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jiagoushi.top/Article/details/gtavyaymud.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtwaztnaqp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtcnbrxxlq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtlfgmxepd.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gtoahrcvzr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtslhaqaeg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtfthbtkyb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gtnprslvog.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gtjvgvrhky.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtwrocarqs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtzxyvmlzl.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gtzlgrotqq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtfsraokon.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtllhgxegh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamcohzqn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtihyqrqfm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtfasxubcb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtyovukxqx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gttihtnysx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtwttfttml.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhyrpqnn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrpuessjz.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gtfnkrbrcn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtgfcflqda.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gteddnhjaa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtazqiknwj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gttyrocyxb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gttltfctje.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.9152youxi.cn/Article/details/gtoxkplsfr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtdragwsdk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gtxdaxylid.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtaknvbscd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtvfgjlziu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtdfpacizf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtkbbjmthc.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtaagfchza.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtkuqcocod.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gtpdqqkcyn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gtgddihote.html


<!-- 参考信息 -->