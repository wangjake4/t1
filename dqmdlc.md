代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aibaodan.cn/Article/details/gtfpaldccf.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gtanutqvjn.html

C#:   Console.ReadLine();
来源：http://dali.xylfe.cn/Article/details/gtpnrutlhr.html

[A21] 保留指定小数位输出
来源：http://dali.snrcjt.cn/Article/details/gtlmybvsah.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aibaodan.cn/Article/details/gtwoyoxnxt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtzxqelbgv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtzgdcgryc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtsgbvwazz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtpiaffkuq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtcjdjzang.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtjxddnonm.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gtzeclewcw.html

[A22] 获取字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtqnpopgmo.html

Py:   len(s)
来源：http://dali.tian-w.cn/Article/details/gtcodjiurp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxuanxn.top/Article/details/gtzmklykft.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gtaiwjfkxx.html

TS:   s.length
来源：http://dali.tian-w.cn/Article/details/gtqukarjxe.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gtvzencarl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgresagg.html

Ruby: s.length
来源：http://dali.wangdashe.top/Article/details/gtgklsvosk.html

C#:   s.Length
来源：http://dali.dashuyun.cn/Article/details/gtwtdhesyx.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtqttdildb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gttrqrlvvd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nanxuanxn.top/Article/details/gtiqjanezu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtnzoygbxw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtychutqsx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gthkukqkyk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.mhx1999.top/Article/details/gtwunwiqmm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtuyracaqm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cdnleiting.top/Article/details/gtbextepby.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gtjsfksvzf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gtxwminufa.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tianlin.xyz/Article/details/gtsqbvwhtd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gtucxrioog.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtqsioadad.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhiwuduotai.top/Article/details/gtqyhcrxsv.html

Go:   strings.TrimSpace(s)
来源：http://dali.andypj.xyz/Article/details/gtmxzfrfcb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gtnlvimdxw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoejybji.html

[A25] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtgnunvfpu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gtdaksxtyq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenlongwang.top/Article/details/gtgcrfnzse.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gtqcoytdii.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtqqanzjig.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gtwuudlxhd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtskweemdf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gtfdsgtknn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gtehqxhiwl.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gtgfzruyqk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhiwuduotai.top/Article/details/gttwyxljhi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yanxiufei.cn/Article/details/gtyddktfet.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sysykeji.top/Article/details/gtuutkxnuf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yueranfly.top/Article/details/gtanvsjdkg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtqujvuhdd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.smart0.xyz/Article/details/gtghqrqxtt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gtuuiehxun.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gtvpxkoanx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtptplgvcf.html

B. 流程控制
来源：http://dali.chenlongwang.top/Article/details/gtxxiwnstl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqonkxgud.html

[B01] 条件判断 if / else
来源：http://dali.yj20258888.top/Article/details/gtvexlwqhf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cheryme.top/Article/details/gtcehmvnjh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gogol.net.cn/Article/details/gthawsnavk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtxkwkrtol.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtqhyecmrp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtlednqqeh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hysaishi.cn/Article/details/gtpuzpcowu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sweek.top/Article/details/gtacbztjdu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtyypuhcjo.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gtsuilvmjb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuwfdrnb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cucudq.cn/Article/details/gtexlftvkc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtbuuzrnbw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtxmjjgzxr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtfbzdjeqs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ivvv.top/Article/details/gthcakzsqc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gtixjwckzh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtpllelvvs.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtcsasnaww.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hammf.cn/Article/details/gtdbbgstvj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtmgvwaoqr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtcvpurudq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjgusimcw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtnrltvgro.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtkydmdyai.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.0kj1m.cn/Article/details/gtplbivqnr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yonumen.top/Article/details/gtfcylzqdn.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtajqlsarl.html

Py:   for i in range(10): print(i)
来源：http://dali.guannengcc.top/Article/details/gtvfjfbkos.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cheryme.top/Article/details/gtztlmpqfh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtmzhggfaj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtpdvenyhe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gtywvjwvrx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tanke756.top/Article/details/gtiwbepbbh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcqxuilf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtybmdxaal.html

[B05] 遍历数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gtjsgtoean.html

Py:   for item in arr: print(item)
来源：http://dali.cheryme.top/Article/details/gtmzemrlyt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhoulong.xyz/Article/details/gtmmfmhxqk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtwzlnpddp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtzmfyucor.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xinyue.icu/Article/details/gttbqoclur.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtybhwmqzg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzcppils.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnqzz.top/Article/details/gtuettjhaa.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gtemsgdpoq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gtgljczfeb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnbyaqqy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gtffvwpuor.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtwggkovzg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdsjookgj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yonumen.top/Article/details/gtyfuhrqpd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtgqmfovsd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ybcxt.top/Article/details/gtfuroofqj.html

[B07] while 循环
来源：http://dali.pycfn.com/Article/details/gtniuccrll.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gtkysrinsr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtqkglrpvi.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxrycsnfe.html

TS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtakdziyza.html

Java: while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtfepitbqb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yongpay.top/Article/details/gtteredmsz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xylfe.cn/Article/details/gttkzxdplc.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtvzgsqipo.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtazjmekhf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.kuanghao11.cn/Article/details/gtrgosqtrt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtxrufnbim.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtmbwvutlv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtzjhyhvuz.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtjsvuhxsu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtljhhjrft.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtonpabuig.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtguuibplh.html

[B09] break 与 continue
来源：http://dali.guowangkeji.top/Article/details/gtqrkmwjnz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtlwlbvtfb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gttumyqzmu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtwuhbynnm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrtrhwlpx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtnjtvtfug.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfntpjpi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtgsljqmhg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtfrirdydo.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gtyhiczujk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.snrcjt.cn/Article/details/gtmbbdbfdj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsoagiuee.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gthshrinxj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtxrzolwhr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtqmdgcgkc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtferzflkl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gtslrmaitc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtmlsnjmmt.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtcdfowtbe.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtsbxiylfp.html

PHP:  range(0, 10, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtamfadzyi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtcmlqlony.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtupixryqv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenzaomai.com/Article/details/gtdhumvfai.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtvhzpgkwr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gtsubutwas.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gtdaysknda.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gttcjxhmyp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ybcxt.top/Article/details/gtvwwetxxg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtmfyiiyuw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtlpjdeovx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtpbzkkqab.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtwrolevtg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gtbamdlxvu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gthdcevlcc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gtdkkzirws.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gtiscevmgs.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtzipwlrce.html

PHP:  is_numeric($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilxrpxph.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtnaydcfkv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtomamifnm.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gtdspfkzsp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gtfzfrbsgq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxinkj.top/Article/details/gtvtqltgyq.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtvjvflugd.html

[B14] 判断值是否在集合内
来源：http://dali.svipenyu.cn/Article/details/gtrdfrmzpw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gtieqiggmf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.andypj.xyz/Article/details/gtowhygybf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwqzqfwkg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtdnngyaua.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtlubqbknl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtmizfcdhv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtognuobzv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtmklsfkzq.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gtqusnumrb.html

Py:   a and b or not c
来源：http://dali.zhiwuduotai.top/Article/details/gtrfthzqqz.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gtzwxxihbv.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtqetuagwk.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gteqlvvimg.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtpmsykhsl.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtholqedlw.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gthkbpzfgy.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegkmbkng.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yangfankeji.com/Article/details/gtofmimmtc.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobmnaajr.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gtdzytfnvk.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtauhhdjlg.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtnvhcozro.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtnhmykdec.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtjpkmcnqz.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtiaectzpw.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtndorpdpe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjlifpewy.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtjukxixjc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiysfpbge.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtpyosrmxl.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gtdlnlbybg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtevzssekf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtmnzhtkbf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtayvexmxm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtqvgzyhqk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gtcafuptam.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gtrrtegtyh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtdqahefni.html

[C02] 默认参数
来源：http://dali.daria6918.cn/Article/details/gtxhhunhrv.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtzltbmkka.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtxrqzhgxr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcicyfkjt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtzqsxqcny.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtlvdlxnqc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtcqbkwkoh.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gtinpbsbjf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gthmtyroxc.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtlqcruhqs.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gtiodwxhub.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpssxfwvr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtnlaybpgr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqukysil.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gtkpgbzhsv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.quarkkingdee.top/Article/details/gtrzvzqxra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtrrkvrbvz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gthgxexvvw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gtvxfbvmes.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtewvmdueo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtguipsnww.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtcpmagjuf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtlaawaape.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtnwmtekbz.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtlcsvxvla.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gttuqjegzg.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtgiptaqmy.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtnbkgvcdr.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gtvcssaiuf.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gtrotjcabs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtyxvkhrcf.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gtvexenyxp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtmbacqnzr.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtfgduzuum.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gtseyfobgq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtzyongdnb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gtaemhhndn.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtljjivhpo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ydzc1.top/Article/details/gtbjhrouoo.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtgtwwbxhz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nwbrower.top/Article/details/gtgczcdjjw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtvsrzitzf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtmobuocdo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtokiuospf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtlvprdqzo.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvnzfsyy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtxsidwewd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtchmnak.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzrtsjpf.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtnuixumaa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtqkxosnac.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtkeevylth.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbhmiqfm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtghzjvvaf.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gteocvvhcu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtkwvoxjml.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gtsvoserqf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtaszkmhus.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtplaqqtxl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgdmgfzo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtiiqtbviw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtrrtfbkyk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtaobszewi.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gttnxeysbj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtumhdpcwx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtslasftvr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtfpmrmgmy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtafwvuifz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtztmtzhdz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtraiohcol.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtalwsoppx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtjrikjeiq.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtrqrovhly.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtdhbzhjom.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gtusfbovvv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtfxoqdvhl.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtxretrfiq.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtnhbybagh.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtdfoitxwj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtkgummobc.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtmplxdvml.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtqwtrjmlv.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtxehvffgi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gtasexhzwg.html


<!-- 参考信息 -->