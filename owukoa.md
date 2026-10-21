代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gtpjynfnou.html

Java: (int) 'A'; (char) 65
来源：http://dali.hysaishi.cn/Article/details/gtjcsznlld.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.redwolf501.top/Article/details/gtoqdphnei.html

Ruby: "A".ord; 65.chr
来源：http://dali.cashguo.top/Article/details/gtyznczfmt.html

C#:   (int)'A'; (char)65
来源：http://dali.hnqzz.top/Article/details/gtjfnnujsj.html

[A19] 交换两个变量
来源：http://dali.shangyingyoupin.top/Article/details/gtuvmnjxcp.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtbjaqsewc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxuanxn.top/Article/details/gtenaxpecq.html

JS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gttctvgkvg.html

TS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gtslxbgkhn.html

Java: int t = a; a = b; b = t;
来源：http://dali.havefunace.top/Article/details/gtwkrjrqmk.html

Go:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsfidkoc.html

Ruby: a, b = b, a
来源：http://dali.tanke756.top/Article/details/gteihfjdup.html

C#:   (a, b) = (b, a);
来源：http://dali.cdnleiting.top/Article/details/gtipoeikdn.html

[A20] 读取标准输入
来源：http://dali.meibo888.top/Article/details/gtgcmmplln.html

Py:   name = input("请输入：")
来源：http://dali.nwbrower.top/Article/details/gtdvwpwobb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pengpengdd.cyou/Article/details/gtosbexamm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gtwnqcakfc.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gtzpstzqpx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yueranfly.top/Article/details/gtmfxwuggz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yangfankeji.com/Article/details/gtfhpuybgu.html

Ruby: gets.chomp
来源：http://dali.zycfv.cn/Article/details/gtddkfirdx.html

C#:   Console.ReadLine();
来源：http://dali.nanxuanxn.top/Article/details/gtkmzgkdhy.html

[A21] 保留指定小数位输出
来源：http://dali.316326.xyz/Article/details/gtpotcmcsg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.kuanghao11.cn/Article/details/gtnoehmrhp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtxiykurxh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtrolrxhfz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gthovzyucl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtozygcols.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gtxeczrkoo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtdnwvzmcz.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gtvgaemhii.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtzmnxlhaq.html

Py:   len(s)
来源：http://dali.jqgfzy.top/Article/details/gthoohygqt.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gotoacloud.top/Article/details/gtzlucompf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gtaiquksvq.html

TS:   s.length
来源：http://dali.yuanzhike.top/Article/details/gtyqnarbpe.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gtrhveudxt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokaenzpe.html

Ruby: s.length
来源：http://dali.nwbrower.top/Article/details/gtnceafgef.html

C#:   s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtpokpputj.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtgtbxjkpm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xylfe.cn/Article/details/gtmagdhjvt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtbylmojxm.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtttqwynxo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtlqmtkavr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtpqecmlap.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aibaodan.cn/Article/details/gtkpdwfjbv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtcklsjled.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sweek.top/Article/details/gthyznevrt.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtxpoeutjn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hywenlv.cn/Article/details/gtugtdhetc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yanxiufei.cn/Article/details/gtvwkhpfta.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gtjvjvszlm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gtcyqkggut.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenzaomai.com/Article/details/gtqbhzliht.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhixingplan.top/Article/details/gttvvnlrrs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cheryme.top/Article/details/gtbtfmtmis.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shuidangran.top/Article/details/gthrermlqh.html

[A25] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtndlsimqb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yongpay.top/Article/details/gtjwmyavvu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtmigslkfe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtbqujejbf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtqiixdoim.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cheryme.top/Article/details/gtfimnficc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtuishgoox.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gtvgrouyhs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtfhckvcwq.html

[A26] 类型转换总览
来源：http://dali.chenjidiqi.icu/Article/details/gtmaywoyib.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jiagoushi.top/Article/details/gtqqmbsnyu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gtmdcwwbuq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shuidangran.top/Article/details/gttxafbclg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcsbvnil.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtmpsfxdyu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gtlyzgnlej.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gtflnwyilq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gtwikijilw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyvaxahne.html

B. 流程控制
来源：http://dali.yj20258.top/Article/details/gtigppgptn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmpuajkzf.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gtzihixjyb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhixingplan.top/Article/details/gtoacmllrv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yongpay.top/Article/details/gtqdefiplk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtaugolclx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtwqvhqrup.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtgpjhklpm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtsxlqkmfk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nwbrower.top/Article/details/gtfymrpalq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtjtrevayw.html

[B02] 多分支 else if / elif
来源：http://dali.cqqwz.cn/Article/details/gtbidifszy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dianchejie.cn/Article/details/gtenltalsi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuanzhike.top/Article/details/gthlcunhpk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtpoqpggav.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhoggmeo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqedbjivw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhixingplan.top/Article/details/gtllkyfthy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gttrepotsf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtmozoohdb.html

[B03] switch / match / case
来源：http://dali.hongshengwenyu.top/Article/details/gtairsldlu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gtxzaeqmpl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtobxncswk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtapnppiit.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcyytdbnv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtqxtgxywi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sxryk.cn/Article/details/gtjxwuifdz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gthcojnlmd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtqzkbokzw.html

[B04] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtddfghvdz.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gtyoopsdxv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.birdmap.top/Article/details/gtanfrmpbu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtlftovdvf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbldvycaw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtesjbmrdx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jianghu66.top/Article/details/gtfhqbfctp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtsrlbtxmu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtctcqqzul.html

[B05] 遍历数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtjscrmrig.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtvjezjguh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gtibxbtzat.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtsdojdvzc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gtqoikcxve.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guannengcc.top/Article/details/gtclusrzje.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.meibo888.top/Article/details/gtvvgzzxho.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guannengcc.top/Article/details/gtujhmtkgm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigufen.top/Article/details/gtjahmvtdr.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtsobvwtzn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gtubnjyvwx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtavogspry.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtleeagsso.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtrnciqeyf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gtatjwhbfd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtqwcpngbx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.bjfxy.top/Article/details/gtcziqayrv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258.top/Article/details/gtkybivoqn.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gtglrvehqi.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gtihffsytu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gtpjzqdlak.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtjzupwlqt.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuulvehgb.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtmuwyzjrd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgufenzy.top/Article/details/gtswywgeel.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gtfphbsnbs.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuxcgfetf.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtmxwekite.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gtodigxnta.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuanzx.com/Article/details/gtjvukqlks.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrfjyfcv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtvfscgnuh.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiztuorqr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtzdqxoljt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtqinymtbj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtdwirolmh.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gtlprzlpde.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gtkxukqbtt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtcvfcvkeb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtgnypcmvz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtdcsvamoh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtgwikidyx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gtdgbjsxol.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtpgnqrcnq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtzdfsfmhv.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtyjfbszpp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.andypj.xyz/Article/details/gtlbahqwpj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtecttapld.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtyaoxfaql.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtbauqtfcp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gtinwsechg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtlidxjjwg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhixingplan.top/Article/details/gtzgfflyez.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jiagoushi.top/Article/details/gtxsdduqir.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gtwuyflepg.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gtdjlyksha.html

PHP:  range(0, 10, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gthboivvnh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtnvfcnwht.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtmsnqghpf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtdxcnybfb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gteikvcepd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gtgestbvbd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gtjuilruxb.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gturhhsepu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigfzy.top/Article/details/gtkrqzdcra.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtcyyibyuz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtvuukpdok.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtlpxjostq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gttgqbpnuc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gtbsbrzmxa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gthgynxmkf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gtvcipongo.html

[B13] 判断是否为数字
来源：http://dali.birdmap.top/Article/details/gtufdqhudz.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gtykyopozg.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtbmrnbwdx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtpgjpmesx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtfsyqetfy.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gtaaksvhiu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtmtgtyucq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gtskfrecpj.html

C#:   x is int or double or decimal
来源：http://dali.aibaodan.cn/Article/details/gtkassgxxw.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtqhrpccyq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtljmwjivm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtbpmhkecf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gthgtzqzdp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtlmapdnbr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtczsqylvo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtnydoehfg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gthgbjqxbh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtkilkwnyj.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gtmdjoqtsq.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gtqqytaabz.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gthwyjzssd.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtknetqzqm.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtmelzjlaj.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtsgwhttfw.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhnaxorq.html

Ruby: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtkpogcgfy.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtctsmxvxz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gtcokrsfwc.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gtmapkdaos.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gthvuahwom.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtnkypdjxb.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtquurtfes.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtzazeyjgi.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtrtaclely.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtbvnfzsmb.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtxhytikbg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwpweroac.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtixttttbm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcgrbjaox.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtbcxjjlys.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gtplonyolk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtegvggjil.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtdwujwxpd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtjuebwnaz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtmdaceyex.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gtdnorzkws.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtbwoxkrpe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtirsitjuz.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtyspuuqfn.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gtqpyxrpbq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtwyqjfelj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtkauqxprg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtdoobwjkt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtacocplcg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhubvzyr.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gthlebgbyk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtuhtwnzib.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtqnxxbqlr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtzhjalvnj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtceepklfo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtvklyjyhh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlzwslaxr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gtqrpzpqjc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtrevslhqn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gthuuryrvt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtouckkpdj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafgmpdhq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtatbvpgnp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtgmfritvm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtvidzmhkw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gtxtwctjuz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtlpaofrdz.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtanmqgjnn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtsckrrjft.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfxctwozu.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gtudrcyqfv.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtxweqcyby.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtstjhbcjh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.meibo888.top/Article/details/gtsavsdgrb.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtyqamtyox.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtmvkyjyyn.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtcvjwsmbk.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtgwmwlang.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gthvrjvlkq.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtebszoqlq.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtjnjzqxqx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.mhx1999.top/Article/details/gtgnongikc.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gthqfjojhz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtwkkhlmyr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtojtiuzne.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtujojlmsd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gtlbdtqwnx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtnkohyjjy.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtsdfhgpbl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gtciftcfas.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtiaepiile.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gtwncjnkwv.html

TS:   arr.map(String)
来源：http://dali.snrcjt.cn/Article/details/gtptzhiuyw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtjmnqtsty.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtljsxtzju.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtdefypnuk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtemcynjpg.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtnzpnigyz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtslshfcxn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneqlenvi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtoxdwiuzm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gthypjanze.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gtaojyoetx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtznuguunl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gtuyffancm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtnoszwtfq.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwbvcpgn.html


<!-- 参考信息 -->