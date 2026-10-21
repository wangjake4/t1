代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtssoodvzv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtdpmbtxaf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtwklwtjdj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtfksxbmib.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sweek.top/Article/details/gtaesoovmn.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gtgscwblsq.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhongyouzk.top/Article/details/gtohwwaaha.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cdnleiting.top/Article/details/gtiaeooepm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daxiang520.top/Article/details/gtvkbdngtu.html

Java: (int) 'A'; (char) 65
来源：http://dali.haohaochexian.top/Article/details/gtndguzfai.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hongshengwenyu.top/Article/details/gtrljerbrb.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangdashe.top/Article/details/gtswatpfkw.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gteucckzgq.html

[A19] 交换两个变量
来源：http://dali.redwolf501.top/Article/details/gtfydsychl.html

Py:   a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtvcbgswtb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.smart0.xyz/Article/details/gtyokcaemm.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gturyepony.html

TS:   [a, b] = [b, a];
来源：http://dali.zhengqikj.top/Article/details/gtblckndtt.html

Java: int t = a; a = b; b = t;
来源：http://dali.cqqwz.cn/Article/details/gtgxwbxgpx.html

Go:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gttvgsupxs.html

Ruby: a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gtingdufsl.html

C#:   (a, b) = (b, a);
来源：http://dali.ybcxt.top/Article/details/gtxizlkfgg.html

[A20] 读取标准输入
来源：http://dali.316326.xyz/Article/details/gtanrmwzxu.html

Py:   name = input("请输入：")
来源：http://dali.xuanzx.com/Article/details/gtuuezeemf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigfzy.top/Article/details/gtitvpcneu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fengsongda.top/Article/details/gtokhqgsuc.html

TS:   // Node.js：readline 模块
来源：http://dali.xinyue.icu/Article/details/gtmddepbml.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtrxesknfy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ivvv.top/Article/details/gtzvpnpumx.html

Ruby: gets.chomp
来源：http://dali.hysaishi.cn/Article/details/gtlnliqaqm.html

C#:   Console.ReadLine();
来源：http://dali.hnqzz.top/Article/details/gtgbgszoxs.html

[A21] 保留指定小数位输出
来源：http://dali.tianlin.xyz/Article/details/gtnbunhtli.html

Py:   f"{3.14159:.2f}"
来源：http://dali.meibo888.top/Article/details/gtmjlcngyo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtebilyqnc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtqwsduuez.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcphrdyxu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtfakjrzyf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gteopanxlb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gteydbrwyi.html

C#:   3.14159.ToString("F2")
来源：http://dali.yvedp.cn/Article/details/gtztmavtqm.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gtmfrqshxh.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtiosmxick.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ehwqpu.com/Article/details/gtvvqetxgp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.snrcjt.cn/Article/details/gttuwrrkqr.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gtcpnygakw.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gtlizcqqxt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwppxyfjf.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gtcxsgukld.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gtkpsicdyp.html

[A23] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtqjyyrhgk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yangfankeji.com/Article/details/gtzoglqjlh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yangfankeji.com/Article/details/gtzjpmiool.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtyjftvstm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtbmsxnvvt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gteuaxjzmm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gtauoikhan.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtskwfiejb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jlsjyb.cn/Article/details/gtbwoqrtpx.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcfbhnqo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gtudsmhvlx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hammf.cn/Article/details/gtszuychbz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtvhyojuxz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtxyluhart.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258.top/Article/details/gtdyscncwa.html

Go:   strings.TrimSpace(s)
来源：http://dali.svipenyu.cn/Article/details/gtlaymulla.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ehwqpu.com/Article/details/gtehkijvsc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtfhmhimzz.html

[A25] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtqbwrbbna.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sweek.top/Article/details/gtjfwibxyg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.smart0.xyz/Article/details/gtujqaygyp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gthiceaqme.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtruewdyrj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.snrcjt.cn/Article/details/gtlxklanej.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gtxncvoepi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cheryme.top/Article/details/gtfvjpvdes.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtrcctwxsc.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gtfovghawn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gtqulkexdn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yonumen.top/Article/details/gtektnblvy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shuidangran.top/Article/details/gtyxnjgnxm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gtkkhzoqzn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgszibsed.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ybcxt.top/Article/details/gtetfbkchy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixemauzy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gtehogcojr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvwhcwbkh.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gtbzhuknat.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtncktiafe.html

[B01] 条件判断 if / else
来源：http://dali.yueranfly.top/Article/details/gtulwdlzsh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenahcxmp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gtmctufwhi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtgumscvoc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtjagmbczh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtvjmxxlbz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnqzz.top/Article/details/gtoiqwnrym.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gtlxurxvkp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtsjzwffwf.html

[B02] 多分支 else if / elif
来源：http://dali.redwolf501.top/Article/details/gtyvvbuntv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gtlxuvrqzn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gtmlneigna.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gthfemalgl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtutalllli.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gttdnrxrds.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnxiangtu.top/Article/details/gttbqtkcad.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gtzckewcuy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtefjiocgl.html

[B03] switch / match / case
来源：http://dali.zycfv.cn/Article/details/gtsqywwulf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangshuangyany.cn/Article/details/gthdjnkyeo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtvgfjgyrd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtpwecgxcv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtbzelwoii.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtncfahgxz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yueranfly.top/Article/details/gtlwaypscd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gtnvvwxcqx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yongpay.top/Article/details/gtflihzshe.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtvcgnuqld.html

Py:   for i in range(10): print(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtaivfthky.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gtijvvttcp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtmrxppnfp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtyxrqmyvf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gtlzothzel.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daria6918.cn/Article/details/gthtuqrmlx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ivvv.top/Article/details/gtlnvsuwtq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtzlqhaehe.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtndapjjqf.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtaextlhmi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtsodsazod.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtawuclykl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gteiqcauqy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtlcplcsav.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gtbbuoebxf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gtxrnpnrdj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigufen.top/Article/details/gtdlqpdlvl.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtgvmwfosj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gtplnlpfvb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gtldpdurlf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtrlxkmxnc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtcirafpfn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmaouqnar.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gotoacloud.top/Article/details/gtosleoyuu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gtwiqquayx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdkkkcnda.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gtbryipsin.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtoyznxott.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspwohhea.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtjkgtpjkz.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaklcdfef.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtylhavnau.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gtvjtolrxm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ybcxt.top/Article/details/gtdvdsogsc.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtjzdolkvn.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtyundynbz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guowangkeji.top/Article/details/gtkwrbnhwc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtfyoelrab.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtuokynuge.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtregqtctw.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtbkpmueps.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtysnwxjkr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gtmuaiwkiq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtktoowjxp.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gtebduxdkp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gtgnqfadui.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtlgzfvgzc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtkltfbosb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtrrbzijlg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtcgpsjwgm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuanzx.com/Article/details/gtycwmrtlz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gtpjuwdglx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtktgndoba.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gtouaqihbj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtgpqegwne.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtutjrshbp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtjxxxxfyu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtcnwpcvkv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gtsljxyvrg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtkuexxrne.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gtzgviwmga.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gtgqwpgser.html

[B11] 生成数字序列 / 区间
来源：http://dali.iojbl.cn/Article/details/gtydwmfsmu.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gttkkrqash.html

PHP:  range(0, 10, 2);
来源：http://dali.wangdashe.top/Article/details/gtgemrkaql.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gthqdrhssp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtatndwkcs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gthqxivoxu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gtysokraap.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjerszkck.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gtorxphkij.html

[B12] 跳出多层循环
来源：http://dali.gotoacloud.top/Article/details/gthwmzfnrs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gtuooqozlr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtuenpdiys.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtredinfaj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtympwirwm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtjpbpvhrt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtiudzmoys.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gtproullic.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gtildgfltz.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gtrnnrbblu.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtppssbeay.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjpxmhbmm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtzysenuyj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzrxbfbq.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gtnzzaarfi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtzymeqkcy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gtnwotudkn.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbvefsbi.html

[B14] 判断值是否在集合内
来源：http://dali.pengpengdd.cyou/Article/details/gtmsoblarg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gtnexhlqyi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gtyifbislb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtalowkmab.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtrxdobxys.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnqzz.top/Article/details/gtobjtyrqd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtwetogqgm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtoqffsddd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtceomsowp.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gtwqbjzoau.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gtfrcxczpc.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtxmjtyqli.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtdwnzzcxo.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtfovfrnrg.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtpueoobyt.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtvbzyjmen.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtjkevxbhc.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtjxsdlpjd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtzyugvnim.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtbgxwerfd.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gteeqpzeax.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gthgldkwcp.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtkubvtvsf.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtezxzulce.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtrekjfnpv.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtzdrgudmj.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtysgqbiwx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtepzxwnth.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtkytgymyt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxugbulci.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtapxjmrih.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtszkigorz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuutcgkg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtizndcgox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtfalzutzu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtmgtmmyqx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtjgdebjoa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtvpmkldub.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtanaxtlpz.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gttcuqcwjg.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gtmdtfsojc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgshkwea.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtbqzqumkg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtzqvbloxj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtjethqrhk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtrindejaf.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gttnvgbich.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtxmowyeye.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtxxloposh.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtzgkrhrmz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtewrxussg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gttqudxhqr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtmbwfrcmo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtmsqkxfpx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtrqhlhzmc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtzhsocosg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gteslbmozx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gttfmxoayx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gtiueiwrbu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtjgdiyluu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtnyfjtffb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtpldzqjat.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtybiiyags.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gtmnhgitxg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtizjdjcck.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gterbawdfi.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtijxbrpjb.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtngzeyzcf.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtbepzlbnc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtmcpdyxea.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtezhsbjyf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gttpcezymk.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtkjyjbkxl.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtuljvqzyk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gtpnnipibn.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtfhquinsi.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gthgatxdvz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtpehiupxn.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtemgquril.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gtywuunwbg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gturlfiuzh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtszrgenyh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gturyfpnsm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtajsdztwm.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtuwpadcjy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gtprswoqvt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtjtepwhte.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtpjsqurbi.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtavmzzhqd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtmyeggszk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtvdftkjfm.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtjkbjljmo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtrrfaagfy.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtuqkshget.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtasqindrz.html


<!-- 参考信息 -->