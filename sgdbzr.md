代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxallfjqd.html

Py:   ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gtnvqoevwa.html

PHP:  ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gttksxsgge.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gtjhsdzdxg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gtmeegfxfn.html

Java: (int) 'A'; (char) 65
来源：http://dali.sysykeji.top/Article/details/gtvpedzuly.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvodrakw.html

Ruby: "A".ord; 65.chr
来源：http://dali.xziqi.cn/Article/details/gtgzrwszca.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gtmtweocad.html

[A19] 交换两个变量
来源：http://dali.cqqwz.cn/Article/details/gtehzoylow.html

Py:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtvtnqbcju.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhengqikj.top/Article/details/gtdvxfllaq.html

JS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gtjbuclonk.html

TS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gtqjkvmcuu.html

Java: int t = a; a = b; b = t;
来源：http://dali.zycfv.cn/Article/details/gtgnbpsqwg.html

Go:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtdkwzdppe.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gtidkhzlvd.html

C#:   (a, b) = (b, a);
来源：http://dali.yangfankeji.com/Article/details/gtbzlmrxpq.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gtczeongmf.html

Py:   name = input("请输入：")
来源：http://dali.chenzaomai.com/Article/details/gtaqqzpklx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.smart0.xyz/Article/details/gthholkgms.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ppjwa.cn/Article/details/gtbgkqfjgi.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpbvlzax.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.smart0.xyz/Article/details/gtbtklrupv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangshuangyany.cn/Article/details/gtncsstwvn.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gtfwfpcwta.html

C#:   Console.ReadLine();
来源：http://dali.aizwys.cn/Article/details/gtifkzvwlc.html

[A21] 保留指定小数位输出
来源：http://dali.gaohongyu789.top/Article/details/gtrlhjalni.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gtfrihqpcg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoineuzzx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtwxseefqe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtjfqhxbde.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtjtzhtqjk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtxcprvfxx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtzaulmrfe.html

C#:   3.14159.ToString("F2")
来源：http://dali.hywenlv.cn/Article/details/gtyajzjksn.html

[A22] 获取字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtzikittbh.html

Py:   len(s)
来源：http://dali.mhx1999.top/Article/details/gtsazkganh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuanzx.com/Article/details/gtrzwusqgl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yangfankeji.com/Article/details/gtkfswrtdn.html

TS:   s.length
来源：http://dali.zhixingplan.top/Article/details/gttsxmvisg.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gtkwxsqtxn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkbktdxd.html

Ruby: s.length
来源：http://dali.cdnleiting.top/Article/details/gtdbzrwjhs.html

C#:   s.Length
来源：http://dali.zdqjudy.top/Article/details/gtgdvvjzhk.html

[A23] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtzimwkxed.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cashguo.top/Article/details/gtonhfnhyn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.smart0.xyz/Article/details/gthwjkuplg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtoiafnxza.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlrgnxce.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtstmkkztn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangdashe.top/Article/details/gtxwtzxerw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tanke756.top/Article/details/gtkjgerxon.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.quarkkingdee.top/Article/details/gtoofblgab.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtbqikypqr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sufxvd.cn/Article/details/gtmrrlqagy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwaswluyp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtmwrlbywc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtuyofwbdu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhixingplan.top/Article/details/gtzgregtbv.html

Go:   strings.TrimSpace(s)
来源：http://dali.cdnleiting.top/Article/details/gtwygtrore.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shuidangran.top/Article/details/gtneqrofnm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gtkfdpjasd.html

[A25] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtanlmmhho.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gtmtuoktmk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tianlin.xyz/Article/details/gtrvgdywbl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gtmrdemtdu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gtjcijzhcq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtsjkmdbpu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gthrajudvj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gtpdtaamxl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tianlin.xyz/Article/details/gtostnfcou.html

[A26] 类型转换总览
来源：http://dali.fengsongda.top/Article/details/gtfrznkilp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.iojbl.cn/Article/details/gtqtwjhlbe.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenlongwang.top/Article/details/gtrmmofknn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gtnxjfuoge.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnqzz.top/Article/details/gtrpeedeur.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gthjsqmbae.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gtgnydsasy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gtczvgolbq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtuwwzfjeu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwszsfzie.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnybnegd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtiwimzowq.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gtgwhchxpd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gtlvzozqph.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnqzz.top/Article/details/gtuffacuer.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtbfbpfmyy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtbzzjontd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gttlqbywtx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgufenzy.top/Article/details/gtxhrlhzzw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.redwolf501.top/Article/details/gtslvlicth.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtftmczirs.html

[B02] 多分支 else if / elif
来源：http://dali.hnxiangtu.top/Article/details/gtkpfvetof.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gtvmxzfqnz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.andypj.xyz/Article/details/gtoamdvzdh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gthukczfgb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtpdefemus.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtbkohwyqs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gttdjpymxb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.316326.xyz/Article/details/gtklhofhxe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtalrxtgjv.html

[B03] switch / match / case
来源：http://dali.hnqzz.top/Article/details/gtidndlbwi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenlongwang.top/Article/details/gtokjdjovf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtdazduaqg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtsptbddmt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtdvijnljt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gteifmbuth.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gtzjkpgsyw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yongpay.top/Article/details/gtugvdmzng.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gtwfegpfou.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtccewrakt.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gtaanhkwui.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cucudq.cn/Article/details/gtekjvrrfs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gtixqrnwza.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtxkdbwlqf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gtvwqfhuyb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gtgnorbdtk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangshuangyany.cn/Article/details/gtmtgeduuo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ybcxt.top/Article/details/gtvykjtfwb.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtjgmlgcsm.html

Py:   for item in arr: print(item)
来源：http://dali.smart0.xyz/Article/details/gtojgsobie.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gtfuzwmfuy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gtohnypqrb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtissgnvul.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cqqwz.cn/Article/details/gtfrtiabpo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtvtqsdphe.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zycfv.cn/Article/details/gtpovqlkeg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gtygvdyhyg.html

[B06] 遍历字典 / 对象
来源：http://dali.fengsongda.top/Article/details/gtnpswjeme.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomafvlod.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttykjmbyj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtkpldnwin.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gthtbgrzxs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gtftzucqwf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gtxyzbgkco.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gtknkwtcbg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtjekyqlxh.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtjteexnyf.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gtymtebicw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gtkfnzllld.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtshcvntye.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtzaafajod.html

Java: while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtcuukclbg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtvzlackjo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtakzcsrur.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtmkjssgqo.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gtgvshqmtx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gtqzycpnym.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gtzydbjdfl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtrmxyxier.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtmkllyxgo.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtrftidzbs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtadmzfwxe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gtbznbcclj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtwzjchbpg.html

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gtajnkiajp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sweek.top/Article/details/gtcludizmn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtvmtxebhj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtbxpdkizh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtabcdpsjn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtaavuamwj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gtckireuci.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtammfeyfo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtoluhfhft.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gtaltifjzd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gtdiwtvukm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtiaacibgk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gticiusvyz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gtrjzagnse.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gthrzsilax.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dianchejie.cn/Article/details/gtazrjmyyf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtotdyfaqd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jiagoushi.top/Article/details/gtseatarve.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gttyhcadsh.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtpsfcrqcq.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gtjvweuoqo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gttbcrllfu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gttypupyuu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtjzanjsah.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gthrinhnvg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gtvklkuqst.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gtotxonicw.html

[B12] 跳出多层循环
来源：http://dali.hywenlv.cn/Article/details/gtbiaeowml.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gtwemwxdnv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtxtzdwaac.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gttrzfsxyi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtznyxxzki.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtppflethn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gtbnmqfpou.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtvhwszggf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtucydsadn.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gtfxvezror.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gteqnddflz.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gtqopxsgra.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtlrsytmha.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtmhqcvjlb.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtxgrtljrp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtfbebvyuo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtbsybfnsh.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtdfbobtlz.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtilwzjqyf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gtyhjczlrz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtaaltjcru.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtlhavjpyv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkduvmrza.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtkxmvagvw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtqdypgfxo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gtwbpgvcci.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtdmssqdei.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gtotvvjaxg.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtfrzuglku.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gtjqurbwpf.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtiugubexr.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtcrwqoibr.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtdgnhuvfh.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtcmtiqmyy.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtoyqspaws.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtfveoaxbn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gtcnkrzwlx.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gtextcqrsd.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gtbkcvynwz.html

JS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtgvouuizp.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gttlecuyvd.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtxkbtejio.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtoyyffhfw.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gtjxpgmpvy.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtmggzyntq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtytloqzcc.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gtmgzeldrq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpjujnrji.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtggoyqpzf.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtyuntadqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtctgpseyp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtxmzxkscq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwnalkvqf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtnomoadzx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtabexzdtv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsawktcn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtrxjtevpq.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtdbhccgmd.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gtitjclsdr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gtaqpgktsv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvqkjghzd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquhrbczw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtyxcmdwux.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gtajlptshc.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtgorfigog.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtbeooxmvj.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtksuhjgkv.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtozyydskp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtrzusmbwr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtvqcignqw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtunrlcplr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtdojctjjo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtzsamumvm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gtnmeoegtp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtckriksgp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtihzysjtr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtvmbcfldi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxmdkbyu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtulsxvmzg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gtexmttqpp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gtqhnvmgma.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtlwdtzrik.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtswopxssx.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtzhyukltc.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gtmustpvci.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtojgkdkol.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtscejlioa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtcjmyenij.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtmfgdzbql.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtdevaehix.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtitdrydmp.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtkqnuxeod.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtvbcgrghf.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gtfatggdsl.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtfegrkwtj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtcpaxmpac.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtkjueokvc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtnagekvlc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gttrvbgmkf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtibpcbora.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtscnfvqtv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtsveklztk.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gthqdsczss.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gttanbryff.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtsimasypw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtcgflxrpy.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtwzhawcwz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtkqdqzqao.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.vqdsnc.cn/Article/details/gtjdzcexob.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gtwzalapfr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxinmohw.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gtzblokuav.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtzzrlpbkn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtsxchdunt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtwirfdyqg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gttshgzbeb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtcjgisqhe.html


<!-- 参考信息 -->