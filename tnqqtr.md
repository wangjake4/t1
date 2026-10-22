代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.redwolf501.top/Article/details/gtzoxmpsgd.html

C#:   var value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtjfnufqgt.html

[A16] 真假值判断规则
来源：http://dali.jqgufenzy.top/Article/details/gtssxnqgwl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtqxoslxdi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj202588.top/Article/details/gtrnfrhvae.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.redwolf501.top/Article/details/gtvaibydgo.html

TS:   if (!x) {}
来源：http://dali.fzhhl.top/Article/details/gtbaobfpjt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gtpjamwpov.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guowangkeji.top/Article/details/gtzmvthysq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gtupdjgmof.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yongpay.top/Article/details/gtumfnpivh.html

[A17] 位运算
来源：http://dali.gogol.net.cn/Article/details/gtglsrtmgw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtvwicaqsn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtxpeswvkh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtqmwshzis.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtzejovhki.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbxnbrjg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtlyibejdm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtarfwnroj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtsnbrdydh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhiwuduotai.top/Article/details/gtdhptxcje.html

Py:   ord("A"); chr(65)
来源：http://dali.wangshuangyany.cn/Article/details/gtoombfqhq.html

PHP:  ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gtpxqclmfg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.quarkkingdee.top/Article/details/gtdqsuvrnk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gthfsokvaf.html

Java: (int) 'A'; (char) 65
来源：http://dali.ybcxt.top/Article/details/gtucgmrqjr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gtflpbbbzo.html

Ruby: "A".ord; 65.chr
来源：http://dali.aibaodan.cn/Article/details/gtlprukzfz.html

C#:   (int)'A'; (char)65
来源：http://dali.vqdsnc.cn/Article/details/gtmhrzrtkm.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gtmwznphci.html

Py:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gthnvtelnl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pengpengdd.cyou/Article/details/gtsruggbdp.html

JS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtnwhjcjpi.html

TS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gtzvblzalk.html

Java: int t = a; a = b; b = t;
来源：http://dali.hnxiangtu.top/Article/details/gtmzhyqzha.html

Go:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtrqkploop.html

Ruby: a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtfufzhasf.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gtrhrwrsib.html

[A20] 读取标准输入
来源：http://dali.kuanghao11.cn/Article/details/gtxygtpiwq.html

Py:   name = input("请输入：")
来源：http://dali.hnxiangtu.top/Article/details/gtliwdkzfl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.dashuyun.cn/Article/details/gtledtgbem.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jlsjyb.cn/Article/details/gtwgpacrua.html

TS:   // Node.js：readline 模块
来源：http://dali.gogol.net.cn/Article/details/gtgnbjqicf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ehwqpu.com/Article/details/gtegqukcuk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.redwolf501.top/Article/details/gtjueenzqp.html

Ruby: gets.chomp
来源：http://dali.snrcjt.cn/Article/details/gtqkjjetxd.html

C#:   Console.ReadLine();
来源：http://dali.xylfe.cn/Article/details/gtfvnkkmcw.html

[A21] 保留指定小数位输出
来源：http://dali.xziqi.cn/Article/details/gtkjcqyevg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sxryk.cn/Article/details/gtzseukaap.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gthabffgdj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtxvkrovea.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtlzxwlpgg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnewbfdp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclnlzrlo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtbfeczgvt.html

C#:   3.14159.ToString("F2")
来源：http://dali.mhx1999.top/Article/details/gtxttccrhs.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtsssmvajy.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdizqodlj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dianchejie.cn/Article/details/gtmrxzodas.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnxiangtu.top/Article/details/gtxoayoomp.html

TS:   s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhparcgx.html

Java: s.length()
来源：http://dali.sufxvd.cn/Article/details/gtsbvshfhb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtneyojkum.html

Ruby: s.length
来源：http://dali.jinqigufen.top/Article/details/gtylrzmcec.html

C#:   s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdrjeeih.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtjjdasjrz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yvedp.cn/Article/details/gtfzlyayvy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhkqalam.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gttukfwtqg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtlrnuvgte.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtsoyiewaw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.0kj1m.cn/Article/details/gtabzuljby.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtmvamwxmm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cashguo.top/Article/details/gtvbpyewrw.html

[A24] 去除首尾空白
来源：http://dali.hongshengwenyu.top/Article/details/gtskyuvdoz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.kuanghao11.cn/Article/details/gthkrdashh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yanxiufei.cn/Article/details/gtljsihprw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtiasydrto.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodyioahg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dianchejie.cn/Article/details/gthksezhko.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtlaiuccuo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ppjwa.cn/Article/details/gtidbuxbvq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jianghu66.top/Article/details/gtowzmfuyw.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtwoimdaco.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gtgnadgfjh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangdashe.top/Article/details/gtetargfam.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gtfxfjjxnh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtgxpifolp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cheryme.top/Article/details/gteratdfaa.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtexzxhhvm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sufxvd.cn/Article/details/gtozpbhgvd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtxtcrbxgf.html

[A26] 类型转换总览
来源：http://dali.pengpengdd.cyou/Article/details/gtvtkilvrr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtwjvdcfyf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hysaishi.cn/Article/details/gtyaycljji.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fengsongda.top/Article/details/gtrwbyyjrp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gtxlbkjqbl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptmbqzbe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ppjwa.cn/Article/details/gtqhccuixr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gtrjpgmuxv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtgarefjkh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpyanjdfs.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtmzdbawmp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtaszlcxct.html

[B01] 条件判断 if / else
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghtdrkcm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yangfankeji.com/Article/details/gtgczxbopp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtptzpmbsn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtgledrhjg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtrmxhquby.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtwbfukooe.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtdauylsrh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.smart0.xyz/Article/details/gttsbhpjhs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtmieiczfg.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtfteugoyx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.havefunace.top/Article/details/gtpvnuzqjo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yueranfly.top/Article/details/gtafwzswci.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtfigbmqbg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtjpxnzpnt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtpxkpwdjo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.kuanghao11.cn/Article/details/gttbjsfefe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dashuyun.cn/Article/details/gtqsjvkaxu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtpzqmixzf.html

[B03] switch / match / case
来源：http://dali.zhongyouzk.top/Article/details/gtpkobnzvs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gtotshuudr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjofaypsd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtpenzkaif.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtsjszpvsj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtnroeputn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtjdfqabwf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgfzy.top/Article/details/gtelzvehvz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtbwjidogj.html

[B04] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdouqbech.html

Py:   for i in range(10): print(i)
来源：http://dali.tian-w.cn/Article/details/gtikmfanyn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gtrtwjybvp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gtjvttysnp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtsdxigjmi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jianghu66.top/Article/details/gtksdrpbfu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ydzc1.top/Article/details/gtbywbfwmh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.meibo888.top/Article/details/gtqkvdposc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmzvxbvty.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gteudvakpt.html

Py:   for item in arr: print(item)
来源：http://dali.cheryme.top/Article/details/gtxcujpqdy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guannengcc.top/Article/details/gtdmfdisge.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtbdzzisip.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gtlnpeocrn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtwgyqptxn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gtmykyqcny.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxuanxn.top/Article/details/gttlhtbwik.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtcuiercri.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gttnsecfsi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtqbnhglwk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.0kj1m.cn/Article/details/gtigzghwjj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gtapadrcwr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtzjmqkesj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxuanxn.top/Article/details/gtygrkorxz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtvultdbwt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daxiang520.top/Article/details/gtozuklbju.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtweqmhrlw.html

[B07] while 循环
来源：http://dali.chenzaomai.com/Article/details/gtzpipurnb.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gtjlqxzadm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gtubrpjkba.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtsnnkjwfn.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtzgeobceo.html

Java: while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gthqjksfmg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gtvqpcetms.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dianchejie.cn/Article/details/gttlunkuxa.html

C#:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtqtnievpi.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgufenzy.top/Article/details/gtyxketplk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.havefunace.top/Article/details/gtntuuilnj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtydlcasnx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtzvojiesj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtleqwqunn.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzklxbgt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.c1oappe.top/Article/details/gtosmuqbde.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gtruogttup.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtttckmhnc.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtpdofdvlt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtvywboxvi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtypxmckac.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtbkqttqkz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtcfyhhpit.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtfwgdlgvh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtmnfcpgvb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gtoxkdyejd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtnpkfzetx.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtxkodftio.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtbxlevwcq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gtdxtdnoqt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtsndkwtsl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtfclkuhly.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gtuxrezfvo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gtmgmuzdle.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gtpsltyeaq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gthjchkbad.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtzecjyqek.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gtortmqnma.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtevmpisri.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtempmzuui.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtfjonwgkf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovxohlwr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtejhotwyv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.smart0.xyz/Article/details/gtibduxnnr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gtefycmmcj.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtulyznnsc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtdyjtdwui.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjifazvty.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtzniblqeh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtrkhrbgzh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtfbaqphxr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtbsglcbfs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtswxwsj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtvzoqdisx.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtuqoxxxte.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gtecbgujnu.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtazksvqmn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtmxtvtodu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtlnjeglhn.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gtpyhocmdx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gtedmqtkbt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtagbmhkmp.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gtzgmozlyt.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gtsklmwird.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtwystotnb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtvobalkfw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdhzfzug.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gthddsmwiy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gtmbafpjxn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtwycovxjh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbonnyjpt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmgvhxhss.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtonlbhomn.html

Py:   a and b or not c
来源：http://dali.jqgfzy.top/Article/details/gtnnlomius.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gtxmjtgyqx.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtsmbsbift.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gttypdwqhs.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtmoxfhtbf.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtjjzziufx.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtgdcqpfso.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtyjpdmwfd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtastvtfkk.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtjpkunmna.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtidfeuyno.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtorvhxtfy.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtrxnqnzxm.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gthuyvttuy.html

Go:   if data == nil { return }
来源：http://dali.hnxiangtu.top/Article/details/gtbvwsirdh.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtfdcohjkc.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtokzlqfgs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblrlagwu.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gtdocliyhm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxbglhjtu.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtqvcxkscu.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtrorirtkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtjtlzcoyi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtqurkdejj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gttwaaltca.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtcidmdlrn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtuypdngep.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtlddcqnpf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtgzfteicy.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtdstoizox.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gtddqinhlx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtfkrjkhdz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtimowbdfz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtktickerx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrskybfe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtfrxajvuy.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtslvoncbw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gtxvvgwmsf.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtpggjfgpv.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gtgfxnzqum.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtaodmslax.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtfapslyuh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtjeldrahv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtxrjgvgwo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtcgmufqwp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtsjlpogrz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gtwyeyyaig.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtyjypswiz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtheeqdnyt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtorhtijki.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtkrbyfytw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtgurnxntg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtrmehxhif.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlijtcqd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gteqmpaacq.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtgqqdsyut.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtpfpxztid.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtmrdvbgtt.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gtmvuxbzzh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtucpmtnlf.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gthorqhqlx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtazsxmmdo.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtwavccerf.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtegbhbqkv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtlxzkfsvl.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gtrirdfzol.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtegnbazkj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtyejxyokg.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtknuoodtd.html


<!-- 参考信息 -->