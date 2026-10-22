代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtwjfktpkr.html

TS:   const value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtbhmztyet.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fzhhl.top/Article/details/gtfnjlbdnb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yongpay.top/Article/details/gtuguoyyjg.html

Ruby: value = data || "默认值"
来源：http://dali.ivvv.top/Article/details/gtctjclzdz.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtsuktkkyy.html

[A16] 真假值判断规则
来源：http://dali.zhongyouzk.top/Article/details/gtoxuvatau.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sweek.top/Article/details/gtgowdtclu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmbcqoon.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xylfe.cn/Article/details/gtxfztgxvy.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthzbgrtsq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tanke756.top/Article/details/gtftthgfwp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuanzx.com/Article/details/gtfiydxbzt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sysykeji.top/Article/details/gtxehnjucg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.bjfxy.top/Article/details/gtaetdqpnn.html

[A17] 位运算
来源：http://dali.tianlin.xyz/Article/details/gtzsbsgtwz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gthsegvygw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sysykeji.top/Article/details/gttsacrvsv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gttdriklaw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtqksofcec.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gthbpixkos.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtaalaatel.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gteztrovpc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtpgwncqaa.html

[A18] 字符与 ASCII 码互转
来源：http://dali.birdmap.top/Article/details/gtlfmxmehg.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gtzseyuhtr.html

PHP:  ord("A"); chr(65)
来源：http://dali.cdnleiting.top/Article/details/gtklvnoaaz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jlsjyb.cn/Article/details/gtnccowbqc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gterbropgc.html

Java: (int) 'A'; (char) 65
来源：http://dali.smart0.xyz/Article/details/gtgulmnjzh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhengqikj.top/Article/details/gtoflktryf.html

Ruby: "A".ord; 65.chr
来源：http://dali.ybcxt.top/Article/details/gtlbfotvxq.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcavbkhy.html

[A19] 交换两个变量
来源：http://dali.xziqi.cn/Article/details/gtcuiepilb.html

Py:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeohdvsi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xinyue.icu/Article/details/gtvvwagjpn.html

JS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gtprybjudv.html

TS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gtqmhkhleo.html

Java: int t = a; a = b; b = t;
来源：http://dali.jqgfzy.top/Article/details/gtzfgqdbxs.html

Go:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtfmcwfnke.html

Ruby: a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gtvkijglzg.html

C#:   (a, b) = (b, a);
来源：http://dali.fengsongda.top/Article/details/gtkwtizpvc.html

[A20] 读取标准输入
来源：http://dali.yuanzhike.top/Article/details/gtffmjmxeo.html

Py:   name = input("请输入：")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrhphopr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pengpengdd.cyou/Article/details/gtjtcplosr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gtydpooslt.html

TS:   // Node.js：readline 模块
来源：http://dali.fengsongda.top/Article/details/gtmzztrrnd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shangyingyoupin.top/Article/details/gtnwfeynde.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gogol.net.cn/Article/details/gtedqgxibh.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gtscznfhit.html

C#:   Console.ReadLine();
来源：http://dali.dianchejie.cn/Article/details/gtdladhudj.html

[A21] 保留指定小数位输出
来源：http://dali.cdnleiting.top/Article/details/gtpfsclbmt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gtijxtearv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtyskcwyfx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtzxucpday.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtsffqjelh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtohjcjsuw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtrjqrhloi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtqsjoyjxg.html

C#:   3.14159.ToString("F2")
来源：http://dali.bjfxy.top/Article/details/gtmyqqrpin.html

[A22] 获取字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtclazjpmm.html

Py:   len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtenxoikoi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gtoasmpivb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cheryme.top/Article/details/gtcmxbkozc.html

TS:   s.length
来源：http://dali.hnqzz.top/Article/details/gtubdzfehf.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gttfozcwfn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fzhhl.top/Article/details/gtbkjulskt.html

Ruby: s.length
来源：http://dali.wangdashe.top/Article/details/gtnfkvhiar.html

C#:   s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtyrpwindm.html

[A23] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtupzpzjal.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtyicoiexl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gtdxbnvhss.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtnrssgxnn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtihkhwehs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtbkpnphed.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shzxlz.cn/Article/details/gtqlzrpgur.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtyqlimpfb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cheryme.top/Article/details/gtubcvcukl.html

[A24] 去除首尾空白
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqfwrqxu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.quarkkingdee.top/Article/details/gtmbmjmsde.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gtbxhzxlqp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtfyyyxgqr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gttirrkmxe.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hysaishi.cn/Article/details/gtukrizhnc.html

Go:   strings.TrimSpace(s)
来源：http://dali.gogol.net.cn/Article/details/gtdggpgvgi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gtjfeupedh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daxiang520.top/Article/details/gtoiamgajd.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtihegudsz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cashguo.top/Article/details/gtrtkzrckm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gthfzenwis.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtygffodlt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtxzqswrke.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ivvv.top/Article/details/gtepixitiz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gtzcjrrxqu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gtitmfmtxz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtlgibbtyq.html

[A26] 类型转换总览
来源：http://dali.zhixingplan.top/Article/details/gtoygqgeoe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hfpthk.cn/Article/details/gtynvsiflp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xziqi.cn/Article/details/gtzwtclwat.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnxiangtu.top/Article/details/gtebmfvkzi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gtgjkhaxbi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gtlsnlbstp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gzhubu.top/Article/details/gtmcajyvyf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zdqjudy.top/Article/details/gtnfusknoa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtmyuvnwyb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtccuazluq.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gtwrbjgpxs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoudofwsw.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtstiicjlc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtygmuasml.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenlongwang.top/Article/details/gtjbqhjqem.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtemhykauh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtqkoggcji.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtryhfvnhj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gtjatsnmif.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gttenuilcx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtrqetwonn.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtokjykmwu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daria6918.cn/Article/details/gtbbrhswcn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cqqwz.cn/Article/details/gtgguhagmt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtwdavngio.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtiueqlmot.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtjucevgff.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gtiryagxoc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gtqdummujr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gttgabykpu.html

[B03] switch / match / case
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbxrujor.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gtzstfqjjo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtdfsxyksm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtbwijlclp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gthbepfjpb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtptvuvliq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtusscrpoj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gtyhuidszn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pycfn.com/Article/details/gtfmzfrmjm.html

[B04] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtaxyjmknk.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gthdfodiqk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gtvpitufgz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gtljqoomum.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtcigavalg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.svipenyu.cn/Article/details/gtqlukdvtp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gtqncrqmic.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gtoxqjuosq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtyybltrdo.html

[B05] 遍历数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtkmgqoaud.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gtointmuoi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gtxphkwieg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gthmywrdcl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtegrtypnk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoamascmw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fengsongda.top/Article/details/gtseokjtlq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gttmvcayts.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gtzpoudvht.html

[B06] 遍历字典 / 对象
来源：http://dali.hongshengwenyu.top/Article/details/gthjazvetv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtrspofkbz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gtmnoetczu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtafskalqu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gthzdtnygq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtyjobxiuu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtrqgkddhs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gtxmcpetmh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtooxttdcm.html

[B07] while 循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtparnkznn.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gtubzjrzzu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gtvygliwdn.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtmxsnhcwd.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtskhanijw.html

Java: while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtcmmdqian.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtmcfqpaxg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.havefunace.top/Article/details/gtcdcgwupv.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gthvgkcyop.html

[B08] do-while（至少执行一次）
来源：http://dali.andypj.xyz/Article/details/gtimkglidx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gteacdacvx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtnxrqlzjp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gthzexumfi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtmohvjvyo.html

Java: do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtynrueugy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtimeqdsna.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtmdyxbfjn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtgnmiebym.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtyomxwfvi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtrixemsuo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtwkvnytmh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqdkvnfy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzopvnsfn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtfectbujg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gtdiqjxeib.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gthybuifjm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtuiwllwad.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gtgkncgcel.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gtqjofsdfy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gtagaihcpg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtoosyabsu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtvkdjdagw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gtoywltrkd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gttuiuvklr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gtvyphjcaj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtleenorhr.html

[B11] 生成数字序列 / 区间
来源：http://dali.hammf.cn/Article/details/gtxvizeiof.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gtwybidzxi.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtslypdwln.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtomjmyfcf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpanvjll.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gtjtjyczti.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtlcruyfmr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtvhkdlmuw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hysaishi.cn/Article/details/gtfawqahpl.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuicvgcu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioznxtmy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gtmwaqgowq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtcpmkqtjd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtacyvxroj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtvmkkjokw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtuxzsznsb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtpuekrmzt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ivvv.top/Article/details/gtyarsfhrn.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtjgrdbopv.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtwzazrpbh.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtmeemxogt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwftxoep.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtiuoflcex.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtqvzemxwk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gteemgymua.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtaulefgzt.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gtgkqtcpzf.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudxjqpoo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gttjcxbcyy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gtslwzkeyr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtmraqfsev.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtqkdceyzp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xziqi.cn/Article/details/gtivwaezpa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudmqigjw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtdfyxxcwc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtgynnjcph.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gtuvjkfmng.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtjuzocmlu.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gtyochrydi.html

JS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtxdwluuvy.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtjhbcqhir.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtvtoltubu.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtbiraqfpk.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtcndpiwnm.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtzutwndix.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtjsfozeet.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtugaidzxg.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgfzy.top/Article/details/gtrdkbnlqu.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmireyzfb.html

TS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdixhtkkm.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtqxgfbgry.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gtnyfrteab.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtsaayamtc.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtbwiyebni.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtabauhhrn.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtmnaknvjj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvdmfqtun.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtogyetnbz.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtybpejsvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtolkwaxao.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtpcanrjpj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtavemsiqs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtzfbgrucp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtmdcwmwge.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gtvaobzvyq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtbdmaygnb.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gtsctseilg.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gtkmwtrxoc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtycdvjlaw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtvijrrxyu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtmxigaufw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gtynliyulb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.havefunace.top/Article/details/gtdcbugcnk.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gtzeskfrfv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtyxfcjzrn.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gtyzevrlaa.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gtmujespmq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtisaxbxuc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtwvjvzifa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxndqmddg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtfnappume.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtlkagrrbt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtgobeesee.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtyqujwutq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gtsryiacrd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtkybtexrv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtwbzxpwwi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtkrapujgv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gthixhjvtw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtlfvtfmru.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gttgqocfos.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucntdtoo.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtvugxosxq.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtvgihdabe.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtksaidqty.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gtvhoxjkbj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtynkjrhdg.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtbxcnafhz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtodwrioac.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gttizpvwqf.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtanqnobcr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gtrcmkelfx.html


<!-- 参考信息 -->