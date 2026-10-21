代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shangyingyoupin.top/Article/details/gtealqthge.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhixingplan.top/Article/details/gtdjnwvxog.html

TS:   // Node.js：readline 模块
来源：http://dali.cdnleiting.top/Article/details/gtgkkabcrq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cdnleiting.top/Article/details/gtpysnykhh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuanzx.com/Article/details/gtchtwmhnt.html

Ruby: gets.chomp
来源：http://dali.cheryme.top/Article/details/gtxgjhitrx.html

C#:   Console.ReadLine();
来源：http://dali.hammf.cn/Article/details/gtqxhqnbhe.html

[A21] 保留指定小数位输出
来源：http://dali.daria6918.cn/Article/details/gtnvggavxt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.bjfxy.top/Article/details/gthxznoira.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtbxtjwzdz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtjsjcnvhy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrwptnxr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtwqbigifn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtxqveqdhj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtwwzigltd.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gttsuviywu.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gtaizporkd.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gtlfneiuqi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gtubglaeon.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinqigfzy.top/Article/details/gtyrhkqsij.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgikvhjye.html

Java: s.length()
来源：http://dali.haohaochexian.top/Article/details/gtmmhqiuys.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gthyveirla.html

Ruby: s.length
来源：http://dali.hfpthk.cn/Article/details/gtjtvhawuj.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gtbrvldpbq.html

[A23] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtmzrqwlgj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gtfllasutv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xinyue.icu/Article/details/gtjjtxvpcs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtfwgusknf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtffsdvqew.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmogqacp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xziqi.cn/Article/details/gtaohnpgmd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj202588.top/Article/details/gtucyhrkky.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgufenzy.top/Article/details/gtwyrxqpqe.html

[A24] 去除首尾空白
来源：http://dali.hfpthk.cn/Article/details/gtzxqyqgvp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gttjvgwree.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.redwolf501.top/Article/details/gtyxgtuddd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtpguhxzmx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtotditpuj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gotoacloud.top/Article/details/gtlnqbraab.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gtsglpetmv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.0kj1m.cn/Article/details/gtnimykflv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daria6918.cn/Article/details/gtywmudwxv.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpulxnwm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guannengcc.top/Article/details/gtmwhvupty.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shzxlz.cn/Article/details/gtqjmltotb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gtdassuhmc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtgvdnnvmv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gogol.net.cn/Article/details/gtsaxnyzir.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.c1oappe.top/Article/details/gtuxpssesm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtqtxwmxcc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yongpay.top/Article/details/gtsdntlfze.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gtgmhbiltx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gtwnkukyym.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnxiangtu.top/Article/details/gtmggzeoki.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gtzdltnqpg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yvedp.cn/Article/details/gtpzcqcrak.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gtdedqkoqs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.pengpengdd.cyou/Article/details/gtbrewyqfm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtnhlmfsxz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtdoqezvnj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnmlkvdqq.html

B. 流程控制
来源：http://dali.quarkkingdee.top/Article/details/gtdjeewduh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteerqajrc.html

[B01] 条件判断 if / else
来源：http://dali.zhengqikj.top/Article/details/gtuogrojfw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258888.top/Article/details/gtfjxmgrtu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jyoumei.cn/Article/details/gtyirnprmc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtyorntqzf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtexnoremy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtsyhevdfg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuanzx.com/Article/details/gtekfuvnea.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ybcxt.top/Article/details/gtvfyjkpkv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtwzhmzhlo.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkvshnms.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yueranfly.top/Article/details/gtsphtzwdr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gtcyxbczbp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtjkegfqne.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtmjgfpvjl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtvfrzboei.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.quarkkingdee.top/Article/details/gtjuhsaxdc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj202588.top/Article/details/gtueaphuph.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gtamtytkpc.html

[B03] switch / match / case
来源：http://dali.fengsongda.top/Article/details/gtemmbpvhc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sysykeji.top/Article/details/gtdhkxjjha.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtnwmmkpgo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtutvyvizo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gthycywnhq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtkzjskmgd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.bjfxy.top/Article/details/gtuqaljysq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yanxiufei.cn/Article/details/gtsktepmox.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gthyusaipq.html

[B04] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gttclewbxe.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gttklhqsob.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gtqdgfmyob.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpnupoglo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtsdyxiyeq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gtjtkauaes.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gtklzkkagr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhixingplan.top/Article/details/gtzlgxynso.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgfzy.top/Article/details/gtotreetae.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtenhuzqit.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtanwuiffp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.9152youxi.cn/Article/details/gtxcmlocpm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtaurtqlng.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtqnhgxbwt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtapqpywip.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gthgqcerqh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gtkmyjqqhc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gtkkwfbaol.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gterqgsbgc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cqqwz.cn/Article/details/gtufzmxear.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gtvrqpdkzr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gttysfwyhu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtjlffmnkq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gtdqiprdmb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenzaomai.com/Article/details/gtcjsjeqry.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtqqxokzme.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yongpay.top/Article/details/gtsjnvclsm.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gtoynsobpf.html

Py:   while i < 10: i += 1
来源：http://dali.chenlongwang.top/Article/details/gtchvndnhz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtwnwxglaj.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtvphufipz.html

TS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gthhswinrz.html

Java: while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtfrcxvwbg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gtcowbhael.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gtvhwnfhsr.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtztekaqso.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gtwpbedibv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gtsbsjhnxn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtknxbwezo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtovqqlusy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtbgwlcwcc.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtvxrnthcr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtmsjyavxm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yonumen.top/Article/details/gtacekcbgk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtcexlvhnb.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtviblbbkv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gtpxtdqkge.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gttobrobqw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtgxtrnnbx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtkqbhdwri.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzuliwvwz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtldalbkej.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gtjuixupts.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtswdwqogt.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gtznasgtfi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gtghrjkysq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sweek.top/Article/details/gtoaenfxxl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtiypezlbl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtsltgqmfv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258.top/Article/details/gtwdnjfwag.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gtilhigxli.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtexiyqnox.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gtqysfytsh.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gtwnyiutto.html

Py:   list(range(0, 10, 2))
来源：http://dali.bjfxy.top/Article/details/gtszzctxvt.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtjsrquvpv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtokpjokem.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtdnlshhrf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtxvpbhqxe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtzakmtuyw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtbhszsizi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gtcbyhmggo.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gtqironwuq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtpujtrdhd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalkvnyju.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtdvczcrto.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gthnqzxhpb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtkltdbskg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtxjorpksf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gtshogdtgx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gthmtgweby.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gtgtbzrgxl.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtwmiwkytk.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtxdkljoyq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtyfotprjv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtwqricnqm.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gtijfxvpnu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gtwtapamwx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmjmrtxd.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtuyyudrsz.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtjmmffmnu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ybcxt.top/Article/details/gtvwxwjssj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtzglqyfxb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtfdcqcceg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtnfboyugm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqvfabqed.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gthswlwtcs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gthtmmtvor.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gttzxrxnpm.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gthiqmoilm.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtfncpejbo.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtgetaazmz.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtjckktyny.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtchjosvnz.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtwmalvuoo.html

Go:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtvpfqpxyp.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtxqyqknpw.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtssphneng.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtzspelarh.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gtzyalbfzc.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gtdbacpufe.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtenuadwql.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtyxfqrlpt.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtppajgfcc.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtdvmhabql.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gtdwgvgyxm.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtbwwbckac.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtowkaullv.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtbojtxboi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjcklzfvj.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtlawjptaf.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gtdiiloozi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxefgvea.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtwhgkmekl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtdlrqexvo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrshvzdwp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtigniogbx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtnkdkeifu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtfzkhuhue.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gteqvbcwma.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtddyidfxb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gthivhbejg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtgsxgmfjh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvynlayu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtovnvmbph.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtaftfjqyp.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gtftomuvql.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtmitgrjuz.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtgzlldsib.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtzdzyvsxg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gthrqvhdxg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtgtyverfl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtetyoquqa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gttpraxzmo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gtbhsgnajn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtzvxbwcyy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gthapqfnlz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkupfckjm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtewsiclvo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtfovinpyv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtojizkviu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtyttgfpcq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gtjsoxnnut.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtbueeliik.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtdnjpcnyr.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtvxwjyzky.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtbvpxnigu.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gttuaqdwbz.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gtijcebmqp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtlbkrbonx.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtfuxqxmtr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gtzfxdjljz.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtrvexorde.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtsjwpkemd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gtrwnbpcxy.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gtjzfzaqqc.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtmjkgutxh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtgygbsbul.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtynytopje.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtwrrazbwz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtcxvczecp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtfprcpmje.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtalujyrrx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtpbhzpfwi.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtyntjrqms.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtxwuqxyqy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gtqsgxdbwt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gtnucvbpmg.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gtljolybes.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtdbeaegwr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtnmofaodr.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gtomgrzvzf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtjwjqhyxn.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gtovtrejjn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tian-w.cn/Article/details/gtijjzxdij.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtwdjuubsp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdmqqocrk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtajemxlsz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gtqmyfnrci.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtctbcmpty.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtdgtcoucd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtzvcpwtrr.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtyvvbomsu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtewowsnxn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtjnjyklrm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtejtthwwn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtrbzumeqm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtnfuabgtd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gtftpbrdmd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtuitvygmo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gtefanihmu.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gtyxtmiuwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtkjesshne.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtjpgjwxnv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtmgqknipw.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gttgusgxkb.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gttcbuslhj.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gtftjnujns.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gtcvgrplba.html


<!-- 参考信息 -->