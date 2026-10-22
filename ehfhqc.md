代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nwbrower.top/Article/details/gtytmlqbhc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.mhx1999.top/Article/details/gtpnxkpnho.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtevkcarsc.html

[A17] 位运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiqmtcla.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtpaikmywu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenlongwang.top/Article/details/gthlimzgml.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtvnezxzxl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtrczvylsd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtvkrbyibv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtzdupmaeo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtezhhttqi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtfxnmoetz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sweek.top/Article/details/gthsfqmkea.html

Py:   ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gtdczrrjev.html

PHP:  ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gtigiegdbb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtyyvlfcqd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtxydopmuk.html

Java: (int) 'A'; (char) 65
来源：http://dali.ydzc1.top/Article/details/gtlkrqbego.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.havefunace.top/Article/details/gtvwmejvuk.html

Ruby: "A".ord; 65.chr
来源：http://dali.kuanghao11.cn/Article/details/gthhncojbu.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigufen.top/Article/details/gtipvjvydt.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gtkcbxoneg.html

Py:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtuhvkytiy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yonumen.top/Article/details/gtfbfshodk.html

JS:   [a, b] = [b, a];
来源：http://dali.aibaodan.cn/Article/details/gtpwbobizt.html

TS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gtcirwoltk.html

Java: int t = a; a = b; b = t;
来源：http://dali.sxryk.cn/Article/details/gtggofwott.html

Go:   a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gtnfghsyze.html

Ruby: a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtccrtoedl.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofhnbnqv.html

[A20] 读取标准输入
来源：http://dali.zhixingplan.top/Article/details/gtnrccclyu.html

Py:   name = input("请输入：")
来源：http://dali.xuetiantiany.cn/Article/details/gtufqszole.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgfzy.top/Article/details/gtigdrhjty.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hongshengwenyu.top/Article/details/gtcxiijlrm.html

TS:   // Node.js：readline 模块
来源：http://dali.zhoulong.xyz/Article/details/gtjiyrydvu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ppjwa.cn/Article/details/gtnhezlqmo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sysykeji.top/Article/details/gtzpofkmxd.html

Ruby: gets.chomp
来源：http://dali.ppjwa.cn/Article/details/gtlyswmpfa.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gtduvjmueb.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gtuhqtljxt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.feifeiyinyue.top/Article/details/gtfeyeogog.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtkvcmkfzl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gttxntmapt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzizcdadr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtsfwrvtsp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtgkfufsgd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gthqqkphev.html

C#:   3.14159.ToString("F2")
来源：http://dali.9152youxi.cn/Article/details/gtljzlnrvv.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtxmczxbci.html

Py:   len(s)
来源：http://dali.aizwys.cn/Article/details/gtvydlmzwb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sufxvd.cn/Article/details/gtdoxxrtzb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.andypj.xyz/Article/details/gtvqkuztxv.html

TS:   s.length
来源：http://dali.nwbrower.top/Article/details/gthyhfuuzt.html

Java: s.length()
来源：http://dali.hnqzz.top/Article/details/gttnpqdcod.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cucudq.cn/Article/details/gtvvongpvb.html

Ruby: s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gteoyfnqiv.html

C#:   s.Length
来源：http://dali.daria6918.cn/Article/details/gtumiksfqy.html

[A23] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtqbqezhsh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtkrtxlgwu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtsawdvstc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtyvwhelvs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gtotnrinnt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjpomyff.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gtvssaqsgz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtemyjltji.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigfzy.top/Article/details/gttnvfbjyp.html

[A24] 去除首尾空白
来源：http://dali.tianlin.xyz/Article/details/gtarygnzqi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtgaynhctp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jianghu66.top/Article/details/gtmxqkwpge.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gttueklucf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnujogve.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.birdmap.top/Article/details/gtrihdzwaq.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmxqslqyj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gotoacloud.top/Article/details/gtkklciosq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.birdmap.top/Article/details/gtrpaqhzpq.html

[A25] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gthmspkzya.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gtqnzxjbkh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuxming.cn/Article/details/gtcaasuide.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtnsavshqz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtehwecmka.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shzxlz.cn/Article/details/gtjufdtnwf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gthpokofwi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cdnleiting.top/Article/details/gtfrmyxhnk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gthmcqddgl.html

[A26] 类型转换总览
来源：http://dali.gzhubu.top/Article/details/gtyorshhqi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqmjmwgu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cqqwz.cn/Article/details/gtkyxkbokz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gtptbcjkjf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gterwiidwq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtojmagchw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gtcthklxnm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gtjxwqqzcp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtmedzbepn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzbmjjcjo.html

B. 流程控制
来源：http://dali.guannengcc.top/Article/details/gtvcgrnebv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtswghiald.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gtsbdsyzzh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.birdmap.top/Article/details/gtyzgnstmv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtezkvbzdf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtdplzjszm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtakyaofdd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtiwmwhedj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yongpay.top/Article/details/gtkfhafryt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ppjwa.cn/Article/details/gttmlssthz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtcvuehppw.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtqwbbdzjl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gtheaeeufu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjvymdsvy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqowobvmc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtzqpylyav.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtfboyghmt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gtxalotdte.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gtogyzlgkc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtapjwblxx.html

[B03] switch / match / case
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjskhrwk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zycfv.cn/Article/details/gtqurvbgfq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtgluskzeq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtmqgyucqu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtenixigys.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gttlalhzml.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtflwdjexn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnqzz.top/Article/details/gtibxeylrw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtieazaypw.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtohmfpkfy.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gtelipnpti.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.iojbl.cn/Article/details/gtoocsgcdh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthglartvj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtwelkkzol.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yongpay.top/Article/details/gtphnhpbul.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.bjfxy.top/Article/details/gtsisnrgua.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gtgdmfpdxk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfvxvsxmv.html

[B05] 遍历数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtbfsutjdw.html

Py:   for item in arr: print(item)
来源：http://dali.mhx1999.top/Article/details/gtkznfaeip.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tian-w.cn/Article/details/gtmmepdtse.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtclqljead.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtidrostba.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtquwhzwun.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuhudues.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtlkyhsbri.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtijjsbjch.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gteflfpppo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gtssjrrixt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnbjkrcpu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gteuypunlx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtxrbmjiaw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gtbojxgymz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hysaishi.cn/Article/details/gtlenvjpvz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gtftcevbah.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gtpijriwia.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtqhplpqcp.html

Py:   while i < 10: i += 1
来源：http://dali.birdmap.top/Article/details/gtznduswle.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yongpay.top/Article/details/gtahvqkfrm.html

JS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gttuogzbpx.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gttquoshws.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtjdkbnwwh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gttvwbtchg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtciwtfrzs.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtqaycwjws.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtusmhletv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gtjjzpbiyl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtivjesrkb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtjezobykx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbxleyhj.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtupbfkvwi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtkexhpnfn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj202588.top/Article/details/gtytewmrhz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtyhkusddt.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhzymbzg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gtfrwbhgvj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtyrfozqvg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gthssolcud.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtzajygwoq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtmxmkxrbg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtcedzdpvo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtcltxzqiq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtkiwenjlx.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtdpbrsdpd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.0kj1m.cn/Article/details/gtuhqffkcc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtimdksbkw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtuanukynh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtrelyiqwm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtvjielkng.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gtkstttdku.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.havefunace.top/Article/details/gtecjvzvwi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gttvgevfxf.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtfrfnehzx.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gtmmlpedjd.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gttfpapznc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtqlkjihvq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtajisiood.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xinyue.icu/Article/details/gtqapgojpe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gtczikltpl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuziawdfp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gtnuvunyey.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gtlzoqiiww.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdkcxanq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gttxciquus.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtzjwrloom.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtnmldxrer.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtrrobzatm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtgbfvhvuu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqquevjo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtqeuxcshz.html

[B13] 判断是否为数字
来源：http://dali.9152youxi.cn/Article/details/gtkfloztxk.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtvpzxoarl.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gttocdfckj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gthxgpjnek.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtonzknjhq.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtefzhhosz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtcfcfnvpl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtltfjowuf.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtsczapect.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtsxmxktkx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gtrhsbywih.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gttvjmzojg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtxbaqtglz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtnimsxhcc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtihbnisac.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtsgjptfix.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtrozplgib.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtnmrojdkk.html

[B15] 布尔运算与取反
来源：http://dali.gogol.net.cn/Article/details/gtmdndyixz.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gthlgveihw.html

PHP:  $a && $b || !$c
来源：http://dali.haohaochexian.top/Article/details/gtbsnnqshc.html

JS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtgkyyfivn.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfmppkts.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtndmwgwmo.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflfrklnu.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtrqxppseo.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtghmubdxj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gtzgeuasvt.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtvhpactbx.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtczuwhhhu.html

JS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtjjsmtfak.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtlnxpqokw.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtqexgradk.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtzfwfytgk.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gtjfwapijt.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtzcfppmwq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcilvgqe.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gttsbimyyt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvzxgudmc.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtwnrtybag.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gtwwbupcus.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gthdpquwqu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtiacqolcm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtuqprinee.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtfaxowpje.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gtyewkfdzz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gtrahxouai.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtcwffotwu.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtxhrmyyqb.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtixxubjzd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gtjtvedeha.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtbtuktmtd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtvlltgyuz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtyblrxdlj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtrxniptvl.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtcjwbtvas.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtsucxkrbb.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gtmhgehori.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtdqvwysjq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ehwqpu.com/Article/details/gtiobaipgr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtepxqwqhq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtouljtgev.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtxvjdbzwn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtbwqhjriy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtbgxzgdth.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtwucluzbn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtwbtyjzuj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtowubgelm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtoriwzxfm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gthvissncl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtpjqelkag.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gtebrigikp.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gthpdnhgcj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfivvrfjc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtxugymfzo.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtxicvaupk.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtbrjjcrcd.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtayraiizg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gthdfzxlzu.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtmqizggxl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gthnxxxrrz.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtikdvfgjd.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtsvfjsfci.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtpdpegibn.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gtvqcmtcfs.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtsjjcoyzo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtsfenhxtb.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtwlqxlmel.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gtsifkzdzx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtdycinuqp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gteplpkxcu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gteplornsb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzobvwcya.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtjscaroug.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtopndvpjo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtdmgdpthr.html


<!-- 参考信息 -->