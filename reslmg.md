代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gtdmuougwh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xinyue.icu/Article/details/gtsofquqxp.html

TS:   if (!x) {}
来源：http://dali.meibo888.top/Article/details/gtpgrmjbhs.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.daria6918.cn/Article/details/gtnwpugxgs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijspmgoq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.quarkkingdee.top/Article/details/gtgxngthzx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtpwegdipt.html

[A17] 位运算
来源：http://dali.chenlongwang.top/Article/details/gtvgcwtkcg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtolwmsiyl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gteemqemac.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtsltjfdvq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtikhbutiz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtyqcjavil.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtikbuatod.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gttrczmder.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtcowflvdk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yvedp.cn/Article/details/gtjztnjawy.html

Py:   ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtbrfpfweb.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gtgzrarvvg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtphkynrxv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sxryk.cn/Article/details/gtydwuxvbp.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258888.top/Article/details/gtixczlnsn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfomfcda.html

Ruby: "A".ord; 65.chr
来源：http://dali.gotoacloud.top/Article/details/gtwfodtsoi.html

C#:   (int)'A'; (char)65
来源：http://dali.vqdsnc.cn/Article/details/gtlxeacpvd.html

[A19] 交换两个变量
来源：http://dali.xuetiantiany.cn/Article/details/gtkjkqidtv.html

Py:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtfiiiqnlj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pycfn.com/Article/details/gtiifcmqrk.html

JS:   [a, b] = [b, a];
来源：http://dali.hnxiangtu.top/Article/details/gtfksireel.html

TS:   [a, b] = [b, a];
来源：http://dali.c1oappe.top/Article/details/gtuqmarsez.html

Java: int t = a; a = b; b = t;
来源：http://dali.hnxiangtu.top/Article/details/gtcejvkdco.html

Go:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gttztdsqmh.html

Ruby: a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtzsdlrhta.html

C#:   (a, b) = (b, a);
来源：http://dali.cdnleiting.top/Article/details/gtgvbkhhxy.html

[A20] 读取标准输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpisqcwb.html

Py:   name = input("请输入：")
来源：http://dali.aibaodan.cn/Article/details/gtkzfavaxe.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jyoumei.cn/Article/details/gtysloeqsi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jiagoushi.top/Article/details/gtkbbmabhb.html

TS:   // Node.js：readline 模块
来源：http://dali.aizwys.cn/Article/details/gtrcjvskqe.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.c1oappe.top/Article/details/gtqeawrkcw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yanxiufei.cn/Article/details/gtispwyifp.html

Ruby: gets.chomp
来源：http://dali.hammf.cn/Article/details/gtxnpvyspo.html

C#:   Console.ReadLine();
来源：http://dali.kuanghao11.cn/Article/details/gtcngijckq.html

[A21] 保留指定小数位输出
来源：http://dali.zhoulong.xyz/Article/details/gtqwilvzvn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttwcidavm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtbkscmagc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtlvvccgim.html

TS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtiinllrui.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtvgrdlwjk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gthpexwgzp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtqqqpypnj.html

C#:   3.14159.ToString("F2")
来源：http://dali.cashguo.top/Article/details/gtlhxshisr.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gtmqdtbflw.html

Py:   len(s)
来源：http://dali.birdmap.top/Article/details/gtcrffyjlf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqjzvujp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhgtdtyn.html

TS:   s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtifxivajl.html

Java: s.length()
来源：http://dali.yongpay.top/Article/details/gtsnjeeulx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuudionj.html

Ruby: s.length
来源：http://dali.fzhhl.top/Article/details/gtkitqnotk.html

C#:   s.Length
来源：http://dali.pycfn.com/Article/details/gtpbgtkbdf.html

[A23] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtlxfilwvc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvgvhxtz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yueranfly.top/Article/details/gttzuoupwn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtcvahbrhu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtiaqzwccj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gtgjchlbia.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258888.top/Article/details/gtubtpsnhu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtxzsjydms.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shzxlz.cn/Article/details/gttindummu.html

[A24] 去除首尾空白
来源：http://dali.shzxlz.cn/Article/details/gtjlizsgnu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aizwys.cn/Article/details/gthqcasqni.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daria6918.cn/Article/details/gtzaharuxx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtyrcwvefd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gttkteybfj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.smart0.xyz/Article/details/gtjmvymkbo.html

Go:   strings.TrimSpace(s)
来源：http://dali.havefunace.top/Article/details/gtjevvzenf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtpgojbgxr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtwvoibpie.html

[A25] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtrqearpgs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zdqjudy.top/Article/details/gtglpvcwrz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nanxinkj.top/Article/details/gtxcimpmsh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtoishozzl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gtanrqfedj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhengqikj.top/Article/details/gtgymoawyy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gttxxmlkev.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.redwolf501.top/Article/details/gtqqrjsfbm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjyewgdzf.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gtdtdzcorz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenzaomai.com/Article/details/gtddoxupex.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwhfwvui.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.mhx1999.top/Article/details/gtreqhgzps.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gtdzitohdk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gtdqqpydvl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gtunitumpw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtzjrlpvvb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gtbnckemvj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfxyzbebh.html

B. 流程控制
来源：http://dali.zhiwuduotai.top/Article/details/gtskgglvjh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuwforcbd.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gtvohzgfvw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cheryme.top/Article/details/gtlmshvbsa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtzlyrccvj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtrtruhiqm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifsbrkwp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtkvrxlcyx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.0kj1m.cn/Article/details/gtrfycvnvv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ehwqpu.com/Article/details/gtcrppkfhf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtqnxzapxo.html

[B02] 多分支 else if / elif
来源：http://dali.ppjwa.cn/Article/details/gthpysgwlb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ehwqpu.com/Article/details/gtzgjpltak.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.vqdsnc.cn/Article/details/gtspcdflvf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtqvzfezza.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtphhdoryn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtbmcnsjlw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gtvkjeeyla.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daxiang520.top/Article/details/gtwpasvxmi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtpsyztzhf.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtlgybtsjl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gtfxduxkyj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtxfwrndya.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtbcpzulva.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtiewxzhrq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtppbqzqsk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gtpxducsbo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daria6918.cn/Article/details/gtymyusyea.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtwbpkzcmi.html

[B04] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtwstjqufh.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gtvcdowcyj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtaeeylqch.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gtpkluzdhh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtlzisqlln.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ppjwa.cn/Article/details/gtdzrstnkc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gteyziuyen.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtognpmqxp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtmggzwurm.html

[B05] 遍历数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtfbicjexh.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtxknhiwmg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cqqwz.cn/Article/details/gtkehrdlfh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gtjgihmode.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtplezhhse.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtkdwowzep.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258.top/Article/details/gtsutvqewb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gtldmniigx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dashuyun.cn/Article/details/gtblakbchd.html

[B06] 遍历字典 / 对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcojwxcnq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffswtecj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gtccmfklkq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjnseejf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstkhltri.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gtbztcbans.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gzhubu.top/Article/details/gtpfdkosye.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtszxtmpxe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjegnsdiw.html

[B07] while 循环
来源：http://dali.cheryme.top/Article/details/gtgtdgwtvq.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gtfnochldr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gtjqorhift.html

JS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtfsndpalw.html

TS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtuwaduuvg.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtannuecme.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gthjyatnbn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmroolmyc.html

C#:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtkcergtcd.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gtjeaypovw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtecwowpyl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtzslwgmin.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gthkciczua.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtviuidoxj.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtyfcujnfp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtlrqaaelt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gtqbkmxmbt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtyepyfdzv.html

[B09] break 与 continue
来源：http://dali.guowangkeji.top/Article/details/gtkzjvpqza.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gtkwysujre.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtvbhjxyuh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzaoujpo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdqbznevi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtbuvpydur.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytijensq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sufxvd.cn/Article/details/gtsfvcyqdt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtkqcbfwwq.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gtwrutafpq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gthhnuddcc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzkzapfz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxznepdcw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtnafowmum.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtrqowrbly.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtwipxhiss.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gthlebapvv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gtiixyqxmz.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gtxkwaezcd.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gtzzuhpwjc.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtodwfgfrh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtswbmsula.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtgiviwqwq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtayfjjcsg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtjjiakpxf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtwqprcycu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gtelnatdju.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gtfcvsotzw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtqzkvebnp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gtdcppddou.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtpmnsfooj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtmillhffe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtkawcocmz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gttqdzuwkx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtuymbvrrl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtonvyvvgl.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtqlofxxbj.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gtxoecvonr.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtmeqfgipk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtcbkbzpna.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gthwgknvlw.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtguwlzies.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gtgjrkizhs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtjplhylcm.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gtibeujzni.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtdmgkoyzi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeogntri.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gtuknjrvhk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtzcggurzj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gttodxhdre.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtxgoxyjfq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gtglesasxc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogxskuvp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtyswuhvmz.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtihktghgs.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtxmjmsqyt.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtwfjvvvka.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtafduiakf.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gthwyquqhs.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtcydeoptl.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtcaaopfug.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtgsdqlpxb.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtxtlnzsvh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtfctzmlyp.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtdvkkbski.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gtpmqclnxc.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtduqmeizv.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtawptbsdv.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtouhlurqd.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gthxhxnbgp.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtjgemexgb.html

C#:   if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtgsjclmyt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwgycgeow.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtkcpatyom.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpltqjbhu.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gthktxzbsk.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtquwamlyb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtdnimfpet.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtwkzevxmk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtfuxhhbdz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnavjwzwu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhoskxml.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gtsfftwjjz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtdzeqbhaa.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtksauprdg.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gthrtazsfm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjerliulp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtnnttvbqf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtpodztgch.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtpytoxptb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gtnzvcaqks.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtekvbkaxm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtflqcpdvs.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gturkpffbc.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtpdnwwcku.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtusblrjzu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtxrmizdso.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gttxopzhtu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gttnjzawvq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtyueisrwl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtbeeyyjwb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtymjoujqn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gturelhmfk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gtqihspxwr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvtfzgut.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfrnonsj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gtmthoejix.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gtmxbjzjoa.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtpfeqctrt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtrqywsozh.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtjuohvoeo.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtswxpcpuu.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtsjffxqzs.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gthddrsntw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtuwzsczkx.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtqorwdiio.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gtodstzhsj.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtfvrurubw.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtdqkspkxi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtpcivajwt.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtveqtapwr.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtozihgoeu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtvaamswuk.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtgzlmemnj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtvxjuykuj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtuzihmxzx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivmrvkzq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtgrzuvsjl.html


<!-- 参考信息 -->