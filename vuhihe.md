代发 wailian999

Ruby: a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtsqqrdgqn.html

C#:   (a, b) = (b, a);
来源：http://dali.hysaishi.cn/Article/details/gtclxffjhj.html

[A20] 读取标准输入
来源：http://dali.cdnleiting.top/Article/details/gtmjplejum.html

Py:   name = input("请输入：")
来源：http://dali.shuidangran.top/Article/details/gtearyyuhw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigufen.top/Article/details/gtiddqopyx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shzxlz.cn/Article/details/gtyrjfhyfv.html

TS:   // Node.js：readline 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtptvvegrp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.daria6918.cn/Article/details/gtdnffykhg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhiwuduotai.top/Article/details/gtqgfoujzw.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtrwgsifxz.html

C#:   Console.ReadLine();
来源：http://dali.c1oappe.top/Article/details/gtvbqfctrd.html

[A21] 保留指定小数位输出
来源：http://dali.jlsjyb.cn/Article/details/gtvqvrnghs.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhongyouzk.top/Article/details/gtufrftqxi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gteubyuzfm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtekkcxkgi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtkjyarhgx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtpjqheuos.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtrximklfk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxdhjfuw.html

C#:   3.14159.ToString("F2")
来源：http://dali.yanxiufei.cn/Article/details/gternsbows.html

[A22] 获取字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtlshysurx.html

Py:   len(s)
来源：http://dali.aizwys.cn/Article/details/gthmwgvuhc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenjidiqi.icu/Article/details/gtkcocgflf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gtlusrjmoe.html

TS:   s.length
来源：http://dali.gaohongyu789.top/Article/details/gtkonyshgk.html

Java: s.length()
来源：http://dali.gogol.net.cn/Article/details/gtwqfmbfyx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhixingplan.top/Article/details/gtvbwsibve.html

Ruby: s.length
来源：http://dali.jyoumei.cn/Article/details/gtsiviiptn.html

C#:   s.Length
来源：http://dali.cqqwz.cn/Article/details/gtucriehbs.html

[A23] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtegexayrt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtrxxjgpuj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gtgirsdplg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtpdattkeu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtxnneirdx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtotisorye.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.havefunace.top/Article/details/gtydnxksgq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtpvksmuta.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zycfv.cn/Article/details/gtbctkgnje.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvmhdeqo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gtrvroaxlr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tianlin.xyz/Article/details/gtdcjjnzsd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtkvdneerk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtqmankujf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yueranfly.top/Article/details/gtfopajfmv.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuanzx.com/Article/details/gtdxrqheei.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.316326.xyz/Article/details/gtidnmlgzv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtpdycfrlr.html

[A25] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdrjkdnw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtyagpxorx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnzgdwurw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtaanhaifn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtdehhfgzw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tianlin.xyz/Article/details/gtjzehxpxl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gtxdxydmnr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cheryme.top/Article/details/gtxxdpozwe.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtnntucjve.html

[A26] 类型转换总览
来源：http://dali.zycfv.cn/Article/details/gtuuqzdcat.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttzghkdr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gtwxbupwnw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.0kj1m.cn/Article/details/gtqeimrmeg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjgcceyb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gtzhvnszwn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hywenlv.cn/Article/details/gtgjxqdmkw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gtfdrqooio.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gtjxyybxfo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfywqrtfa.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gtlnobkhcc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfeydalij.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gtsvmztgjl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtxtalecgr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuzgjgrwk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtxnyuzern.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtojswnwgd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtlrgskkec.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gtummvewvp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtnbtkjcbp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtaqyhosii.html

[B02] 多分支 else if / elif
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuwfoodt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gtfqqrflji.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gtocxbwxal.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtmiyjmvmh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtctbxewur.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtstcdqhzq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.havefunace.top/Article/details/gtjkekuwwx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gtgioyggrg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gttdhkbhoi.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gtbvwszrqc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenlongwang.top/Article/details/gtgjjgfwfv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gttlqjispm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtempookid.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtwncwfzgv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtitadigov.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtpadhmbqi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shuidangran.top/Article/details/gtrpftufno.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtclgxsata.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtcrcvtjpo.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gtkbilvjwd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtbdagyeem.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtuguejxzo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtjfyhmoao.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtkrgepwzt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gtjsqkwpwx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aibaodan.cn/Article/details/gtuhenskwn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxinkj.top/Article/details/gtieerscbd.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxiehjlz.html

Py:   for item in arr: print(item)
来源：http://dali.0kj1m.cn/Article/details/gtcqptihlj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gtcyxitoqn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtjbyqvenf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtfusuugwr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shuidangran.top/Article/details/gtzcvoihhq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jyoumei.cn/Article/details/gtlkezfeld.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtgjnlxxtz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gtadrtgdpi.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gtebjqbiav.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.9152youxi.cn/Article/details/gtdytmuyni.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.andypj.xyz/Article/details/gtywikhqhx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtmsljippd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gttyvcifoj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cqqwz.cn/Article/details/gtuajewbdb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstfswfdf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtxcfayjes.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtbhwgwrdk.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gtkyyxtvbt.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtxaysadsp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gtkyyaghmr.html

JS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtaokqrnee.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gttwwddaiz.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtaswffepq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gtaxkewqvv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidhnprmv.html

C#:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtnfapttjn.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtwjnjurbt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gtboltkjps.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtlckxwobi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gttxhtpwdt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtwqfqxxfg.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtnfmozjez.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtvpmtomcg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtcvkdesoc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtaxkcwqut.html

[B09] break 与 continue
来源：http://dali.ivvv.top/Article/details/gtrazkcltn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guowangkeji.top/Article/details/gttftxbrah.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtdxzjbyuq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtaznyvvgq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtajzyecvt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gthirnsthj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gtaxtpunmi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtyehrayoe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtifvfhnit.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgfolakp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gtcavxugvh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gtldzjjggz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtxjuxhxwr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtnvyghdtv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gtelimlqpu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtnexufqgr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtxhnvhccc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gticyybqwe.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtksjokthg.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gtnnplzhwm.html

PHP:  range(0, 10, 2);
来源：http://dali.shzxlz.cn/Article/details/gtignmcbpd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraqhdbuv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtrbaqeyui.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gtckzsbzgq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtlrctjbav.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gtdgshpzox.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtfcnrrreh.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtcuwcwkrz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gtpuzemkmx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gtwozybmvv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyksrzhti.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtngosojdz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtyxsluzeb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gtvffyjjzx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtcwvwmfhj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtdttiqstj.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtlbyogepp.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtgcbwaexs.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfkppkbqd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtnpgqntpd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtjkakktxg.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gtuusgjkrs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.andypj.xyz/Article/details/gtmtjcjpkx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtyxvcskux.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gttbkefelr.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gtzksyrpoa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gtxmftfspc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtbjthncjb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtisbjtjxd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtmzwsuvcf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtepjljoyh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykbtemdo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtbodxveko.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtvldqiaow.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtxpfgfgla.html

Py:   a and b or not c
来源：http://dali.sufxvd.cn/Article/details/gteynnryhi.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gtdwiiegam.html

JS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbtenbzw.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtivhoeebm.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqozkgnk.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtfppspupw.html

Ruby: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtbtcyvsbu.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtqerbgjfc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzislwrcn.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtqtbnqnop.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtqpmldxea.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtipmwewhf.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtwxfjolri.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtegipjxzb.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtsdtcsdgn.html

Ruby: return if data.nil?
来源：http://dali.birdmap.top/Article/details/gtaeoweost.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtxlyxjuhd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyafzpsbz.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gtrwsviitq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcvsngeg.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtezewlozt.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtgbygqeml.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtqrjhsrfp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtfooazbcw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtnsrkcvss.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtxgsdjdqx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtgihhydpn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsjenkqw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gttyatkgga.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gtfghgfdty.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtjkgmfbfl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzjvrynez.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtufbawzty.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtuteamxbw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvnzrmha.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcveoqjby.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtuudtuudb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtnpwqugds.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gtdlvjrkah.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtvslhzadt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gthipuxzeu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtyogerksw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsbcxsqq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmarllbo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtwsdpqstf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gtqyudugqu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gtccbxmzvs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtlympuwmp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gthlwzugav.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gtfhbcuafq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmfiqhor.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtwhpbbgrx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gtimobvikq.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtlbygcgeb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtbeewmzmg.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtfveqakgs.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gthbwrtscb.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtasjvmtco.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtkhmiinfm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gttxwtjhqq.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtiukyojxs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvgicdmk.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtkohtxnvr.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtgrinhirc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gtqntmcaba.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gtkaptjuow.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtthnenucf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtcexdkjfy.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtnnobxcvv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtrumppacj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yangfankeji.com/Article/details/gtxllqumdx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gtsqaqbsvp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gtelyjwccl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtgsjuwwlf.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtponefjyu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtflxlxmxo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtkxwtwxfp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpkzbruv.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtqoytzqzy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtxrqlcxgj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gtwuxfsknz.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gtvvyimpld.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtgedjwhpe.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gtfqafucew.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtsyqpqche.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gtdkvuokhs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtyoajwwux.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtiqilyqer.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gthqrhvlix.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gtzimdqmpl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtdyttjfwi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtaofeaqdb.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtaewespyj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtqykkmfii.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtxypolsmk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtaxgzwtce.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtmrkspcug.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtmurwfeei.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtiyicdpho.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtrrmfwojt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebhfqaic.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtapiubzoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtoangcefb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtalbrxjsx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtrkcsxewb.html


<!-- 参考信息 -->