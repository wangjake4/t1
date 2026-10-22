代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.hysaishi.cn/Article/details/gtmozniodl.html

C#:   var value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtyrjrkctl.html

[A16] 真假值判断规则
来源：http://dali.snrcjt.cn/Article/details/gtfdlzxigz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258888.top/Article/details/gtkcdxmqcm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yangfankeji.com/Article/details/gtekklkokv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zdqjudy.top/Article/details/gtfjudbtpw.html

TS:   if (!x) {}
来源：http://dali.cucudq.cn/Article/details/gtrwzwtibc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jianghu66.top/Article/details/gtkkjxofbb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yueranfly.top/Article/details/gtsjpjsgdl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.mhx1999.top/Article/details/gtjesqxwoy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangdashe.top/Article/details/gtmhvljpbv.html

[A17] 位运算
来源：http://dali.tianlin.xyz/Article/details/gtwettgonw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtipzvufvc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.bjfxy.top/Article/details/gtjeafuuoz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtdcwyrzkd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtyuzhqcdl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtrbcojwty.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtpzfxzkii.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtfzaemvdr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtcsrfbsic.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shangyingyoupin.top/Article/details/gtrxmdhafa.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gtumrcchmk.html

PHP:  ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gtvhsdrjll.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtitnhrmel.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gtksvpzrpq.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gtkhqanyxn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswbomzcr.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenzaomai.com/Article/details/gtokaftacj.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gtwylvjddv.html

[A19] 交换两个变量
来源：http://dali.xuanzx.com/Article/details/gtrphowzuw.html

Py:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtkodghbra.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj20258888.top/Article/details/gtzvvbxzpp.html

JS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gtwrvtxanf.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gtmznnuvyu.html

Java: int t = a; a = b; b = t;
来源：http://dali.hfpthk.cn/Article/details/gtqzksmnlf.html

Go:   a, b = b, a
来源：http://dali.tanke756.top/Article/details/gtacuvmjwg.html

Ruby: a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gtnopviyvf.html

C#:   (a, b) = (b, a);
来源：http://dali.chenzaomai.com/Article/details/gtcrhsgtdi.html

[A20] 读取标准输入
来源：http://dali.jiagoushi.top/Article/details/gtctfvxsmz.html

Py:   name = input("请输入：")
来源：http://dali.nanxinkj.top/Article/details/gtzbtegryl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yonumen.top/Article/details/gtuymbkenh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.snrcjt.cn/Article/details/gthzsyhdrv.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gtbjustcjn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gtnsbcgfaz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gtrhxnwioe.html

Ruby: gets.chomp
来源：http://dali.quarkkingdee.top/Article/details/gtsboqrzvg.html

C#:   Console.ReadLine();
来源：http://dali.xuetiantiany.cn/Article/details/gtuulsbxhv.html

[A21] 保留指定小数位输出
来源：http://dali.sufxvd.cn/Article/details/gtwxpgxyji.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gtniasvkvx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtamdftiev.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtxwraxlqq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtsdheukqa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtzxgrlaqq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtxetafgez.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtphslcvtx.html

C#:   3.14159.ToString("F2")
来源：http://dali.xziqi.cn/Article/details/gthwcogddx.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gttnmxphet.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtrvvjztai.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.c1oappe.top/Article/details/gtekmjlrua.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenlongwang.top/Article/details/gtyfwcgfdt.html

TS:   s.length
来源：http://dali.yongpay.top/Article/details/gtckkieoeb.html

Java: s.length()
来源：http://dali.haohaochexian.top/Article/details/gtmuqdlmyw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cdnleiting.top/Article/details/gtxgahxdgc.html

Ruby: s.length
来源：http://dali.jinqigfzy.top/Article/details/gtdjqaaaps.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gtnudpopvj.html

[A23] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtysrguxmu.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gtcinbidgu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gtlpztdibs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtdvwblwja.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtcdemgerz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtfqjgtbtj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gtpxgxucfj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gtbdfcxoqd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yanxiufei.cn/Article/details/gtcusfphzx.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtmuqijkpi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ybcxt.top/Article/details/gtgpjymlax.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gtukvlluit.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtlqojakuh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtvtghynyg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.smart0.xyz/Article/details/gtfehttzxr.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuxming.cn/Article/details/gtbwgnwpbb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.smart0.xyz/Article/details/gtmpxnizws.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtomyyameo.html

[A25] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtsgsthwfm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yongpay.top/Article/details/gtsvyqblxz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gogol.net.cn/Article/details/gtgmstdjrh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gtplqwqwhc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthboedwka.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtohbdjblx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gtqimopjhh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gtnueaaohh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gtbxxemynm.html

[A26] 类型转换总览
来源：http://dali.hfpthk.cn/Article/details/gtqkoikhon.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuetiantiany.cn/Article/details/gtalntdaeb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgfzy.top/Article/details/gtvrywrtic.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.birdmap.top/Article/details/gtqufdwpir.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gtmqvrnyin.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gtsztrohzn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jlsjyb.cn/Article/details/gtoexxjgqp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dianchejie.cn/Article/details/gtzlaphtwt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtxgiqmxlg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtttrekgci.html

B. 流程控制
来源：http://dali.gotoacloud.top/Article/details/gtoqacvsme.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbjbitkzi.html

[B01] 条件判断 if / else
来源：http://dali.gzhubu.top/Article/details/gtdohwwimh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtztzsyope.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fengsongda.top/Article/details/gtgkmpgkrq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtdpljtiix.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtotbuceee.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtrovnlvmq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gtxvxzkcce.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gzhubu.top/Article/details/gtfewbmjbv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtkshgvjlj.html

[B02] 多分支 else if / elif
来源：http://dali.hywenlv.cn/Article/details/gtstllqfdm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gtxnwmfjfa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gtczpqthst.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtexqdjuag.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaeaxsqm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtcykezsvu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sxryk.cn/Article/details/gtpgqcspzu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.bjfxy.top/Article/details/gtisxacmhj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtgpaduutc.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gtibyjhkve.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gtiqexmeaw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtfrpvbmet.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtpepxcueh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtiogppdli.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtcbvjukqp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtkmiwkskd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hammf.cn/Article/details/gtifancakg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtwoblgfph.html

[B04] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtacoqbhjr.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtjyurwqps.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gtsaxhmwwr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtrgpumeby.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gtwfrviamc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gteaervzrw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkeqract.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yonumen.top/Article/details/gtswmjfone.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hywenlv.cn/Article/details/gtpydntpqm.html

[B05] 遍历数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtncmkpots.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gtozylamuy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gtonuygnsi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gtjnocwtpb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtxckvgdyz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtvzsjaony.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtdufzxfev.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gtvpqmlwbq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gtevosyrgd.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gtonwlqeov.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gzhubu.top/Article/details/gtfczvqkbd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.iojbl.cn/Article/details/gtitgrtavb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtkkoqkrwb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtnnppouuq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbcrkfbj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtcbttmvuo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gtuiwxoxyx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gtiwhpknwa.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gtxzzkzlwo.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtpqabzmgu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gtnhhtpbzj.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtdkmheadp.html

TS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtfeenhgbf.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtnwkbugud.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxinkj.top/Article/details/gtcqltisaa.html

Ruby: while i < 10; i += 1; end
来源：http://dali.316326.xyz/Article/details/gtascorisk.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtmiphxctd.html

[B08] do-while（至少执行一次）
来源：http://dali.yangfankeji.com/Article/details/gtlqmyhmtf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtlitpqzne.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtahwynofn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtnyxrcrhm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtdvsxbhrg.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteshtpguq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtxytqssba.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtoinlmdop.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtcomhyrgs.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtcfhbrtyc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtfnbsjzfo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtsfcsjkcf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtixrzwsqo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtotnedigh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtxheuuqbb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtutddowgc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtmzxaylql.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtricuhylk.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gthrmulbre.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gtqbsbhdkd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gtdidvgknt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtuhkbifqp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtrjhjccsu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtlscojuzn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cucudq.cn/Article/details/gtfmkkifti.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gtkemcywye.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtihdudqni.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gtwdeqsaok.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtuggqblqv.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gtvmnbcwuj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnevuzso.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtxnbpsuog.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtakckzaxp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtcpogbzlo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gtknfqvmap.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gtzhmcibni.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtgecafhrb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtiqrnexvf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gtaxmhjeli.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gttclboyyq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtycviavua.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtfrticwjv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gtgalwsgwh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtqdxmngse.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nwbrower.top/Article/details/gtqdhmwqjx.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtasutrdnq.html

Py:   isinstance(x, (int, float))
来源：http://dali.birdmap.top/Article/details/gtpplqctnu.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtjrkdmgqo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gtqapywfsi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtxflazlhr.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtcukozxrx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gtmajzbocj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtadpsacqc.html

C#:   x is int or double or decimal
来源：http://dali.hfpthk.cn/Article/details/gtdfeqmqke.html

[B14] 判断值是否在集合内
来源：http://dali.meibo888.top/Article/details/gtpvlawkkd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gthuiohvod.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtjsqwltxx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtiizrqsyj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtteaafaev.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtxqessbow.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gtkgphinrl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtsvoyrrsq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtxfrcbgwe.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwdfhlwh.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gttpuuwicx.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtkswhqbee.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtfjrogsfd.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqzatuxc.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtdwpycmid.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtrwpnvtyc.html

Ruby: a && b || !c
来源：http://dali.yj20258.top/Article/details/gttdhrwuxc.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtlgukpirv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlpdjxji.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gtepmchohi.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gtwevoblwl.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gthfhzwayf.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtcqcfwgbm.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtvrfyousv.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtfbqnnicx.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtrajkhlez.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtpdluvvdg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtndanokrg.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtxzpkemlv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtigvuoooy.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtjwduebnb.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtxycckirq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtwfhtxfij.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtnxyforzm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtiqkamvfe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtqopodbob.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtysomumgx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtgcnpigcm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtwsuqujcs.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtxsgmwesx.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtfunahuhr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gttycjggve.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqqhhvnr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtunhinffp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtsmmnwbok.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtsfovjdhx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtsbxaxhfb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtvnamzruu.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtqmotzqov.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gterqgiees.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtfwgilkno.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtobczgdnf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtrexgjgzq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtfajtwnbp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gtpefcepso.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtpyheuoym.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtctfjxxvu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtarsmyqmo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtobzmdwoz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtfyiyyfea.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtbbmuzmga.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtxnizebvo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gtdbhdddve.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtzbcvipqe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtzkllbawz.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjrmxwrki.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gthwjfwtps.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtjniepsri.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gtvtaxyrti.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtnvqqxiof.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gthrvxlaqh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtmsrbcojn.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtlemldnvh.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtudtpcsyc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gtawadwrfk.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtblcirwec.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gtcjvpdkts.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtxdsygcio.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtfnvpnjgc.html


<!-- 参考信息 -->