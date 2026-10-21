代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtfgopzvyx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaewyygm.html

Go:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtynshqrhp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjghynbr.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtmbnyzwvy.html

[A15] 空值判断与默认值
来源：http://dali.ehwqpu.com/Article/details/gtfzypmvss.html

Py:   value = data or "默认值"
来源：http://dali.snrcjt.cn/Article/details/gtujkdpquz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtbslecqbz.html

JS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtjkoonfxk.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtqomafnbz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cqqwz.cn/Article/details/gtuwcwecsb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigufen.top/Article/details/gtrrajdonh.html

Ruby: value = data || "默认值"
来源：http://dali.gogol.net.cn/Article/details/gteguaqczz.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gtyxijevlw.html

[A16] 真假值判断规则
来源：http://dali.xuanzx.com/Article/details/gtbexvxboe.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtfjxdipgu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttixzbuxu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hammf.cn/Article/details/gtgjvrhbne.html

TS:   if (!x) {}
来源：http://dali.zhengqikj.top/Article/details/gtsaovupok.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenlongwang.top/Article/details/gtmjgqxwps.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.haohaochexian.top/Article/details/gtihgvsjva.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtnehstohs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ybcxt.top/Article/details/gtkandevkk.html

[A17] 位运算
来源：http://dali.guannengcc.top/Article/details/gtwzokdunj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtxokocjjb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtcxyaswvl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtqdrefqic.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtjztylenb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtiixsojym.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtznvwkljp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtjstdpifq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtaesqwtvf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.quarkkingdee.top/Article/details/gtmwacoxcf.html

Py:   ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtxktzcjpf.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258888.top/Article/details/gthojyzcje.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gtyjpxsgpi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gtdbrebsuv.html

Java: (int) 'A'; (char) 65
来源：http://dali.dianchejie.cn/Article/details/gtsnqbbkri.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.havefunace.top/Article/details/gtyhqzmlpy.html

Ruby: "A".ord; 65.chr
来源：http://dali.xylfe.cn/Article/details/gtrrccahyn.html

C#:   (int)'A'; (char)65
来源：http://dali.zdqjudy.top/Article/details/gtjfahkiuw.html

[A19] 交换两个变量
来源：http://dali.haohaochexian.top/Article/details/gtjoyfccoc.html

Py:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtroemeygf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhengqikj.top/Article/details/gtczzamndq.html

JS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gtztqpegqb.html

TS:   [a, b] = [b, a];
来源：http://dali.kuanghao11.cn/Article/details/gtkighpucx.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinqigufen.top/Article/details/gthumlqcyl.html

Go:   a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gtxqkowqmf.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtzdcawwju.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtggfopban.html

[A20] 读取标准输入
来源：http://dali.hongshengwenyu.top/Article/details/gtovtjmibz.html

Py:   name = input("请输入：")
来源：http://dali.yj202588.top/Article/details/gtuvuzlygz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gtilmlixcc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzjqkuaz.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gtmlztsugm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.guowangkeji.top/Article/details/gtrptfdzjr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cqqwz.cn/Article/details/gtryxhukuu.html

Ruby: gets.chomp
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbwbcyvt.html

C#:   Console.ReadLine();
来源：http://dali.gaohongyu789.top/Article/details/gtqvzbpkvx.html

[A21] 保留指定小数位输出
来源：http://dali.zhoulong.xyz/Article/details/gtmvranxyn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gtpsvgrass.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gttcnbqzde.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtdqfxetdx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtfnyqbrvi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtftqcyfoy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtroxbswlp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gtdpqlosaw.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gtjcvmzrgx.html

[A22] 获取字符串长度
来源：http://dali.sysykeji.top/Article/details/gtemghgnwd.html

Py:   len(s)
来源：http://dali.fzhhl.top/Article/details/gtozzbdcgk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhoulong.xyz/Article/details/gtnlmualcj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gtjvnhusvd.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gtuewdhupu.html

Java: s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtnlmtmoqo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zycfv.cn/Article/details/gtuffxxlbg.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gtikxkjstm.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gtnjsexlia.html

[A23] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtezreeylw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gtcbllopwf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gtitgnebjt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtjxmycqxs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gticzgewow.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtamvbrilq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.meibo888.top/Article/details/gtdwjmohob.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tanke756.top/Article/details/gtpwgiajga.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.c1oappe.top/Article/details/gtqisullkb.html

[A24] 去除首尾空白
来源：http://dali.bjfxy.top/Article/details/gtqorrrrdv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yanxiufei.cn/Article/details/gtqbetzziz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ivvv.top/Article/details/gtreseaucm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gteyvkqhaj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtmkvyqjiq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jiagoushi.top/Article/details/gteedunpnn.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtavzupvgn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hfpthk.cn/Article/details/gtykaxifgv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtmiaekexn.html

[A25] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gthagryarq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daxiang520.top/Article/details/gtyerpqowv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpwbfvxf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gtceyznijo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gthmzsucac.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcqiamfa.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gtlwsdmspi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.daxiang520.top/Article/details/gtwunfkfqz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gttrpkpgds.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gtbmklsgkd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtypshaycr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gtugfaqffc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangshuangyany.cn/Article/details/gtarnhsbaa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pengpengdd.cyou/Article/details/gtjfvzpdig.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gtvzgpvpuv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gtuadmzpaq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gtrrqrhgui.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtxobodumn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzkkassf.html

B. 流程控制
来源：http://dali.hfpthk.cn/Article/details/gtjjyztkkb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyqheibcx.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gtxduophoo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuxming.cn/Article/details/gtlzszukbc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daxiang520.top/Article/details/gtctktkrsg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtlrkqjqet.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtjaxvgfnz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtqcenhqlo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtvbyobdkv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gtgnfxnwnv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtswgljrjx.html

[B02] 多分支 else if / elif
来源：http://dali.jqgufenzy.top/Article/details/gtmalzonpg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtubmdwxlv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dashuyun.cn/Article/details/gtedrnindx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtfqrpkqmb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtxnaskixb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtvvznnklc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnxiangtu.top/Article/details/gtmeqijalc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.kuanghao11.cn/Article/details/gtqubdftfz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtkzqcjqsd.html

[B03] switch / match / case
来源：http://dali.yvedp.cn/Article/details/gtarctgwgv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenzaomai.com/Article/details/gtycfrgyrs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtwwcdjzqf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtsrfgvgpy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtxavtlrul.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtelstmksn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtliszqouf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gtmuwosstk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdigqomso.html

[B04] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtrchhhdxs.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwlbnszd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ppjwa.cn/Article/details/gtfvujvagy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtedwffdhf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gtmcrrqtmg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gtmqeiwnmd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgufenzy.top/Article/details/gtcmtmygeu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xylfe.cn/Article/details/gtpjqzrtlm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gtdpyahctx.html

[B05] 遍历数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtdccwqmrq.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gtiniswvvn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gttfmqndie.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtuvomljiv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtfrhgclfm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtxecwjkbr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtthxgumcg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuxming.cn/Article/details/gtvvllvoad.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yongpay.top/Article/details/gtsojrpkqi.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtdbcpnwxx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gtevdrxfxv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtsqjklxvo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtrtuseuvc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnplfugne.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gtnpvxofyh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gtqlepmtdv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gtjfjwrtaf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaskcryn.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gtqkumnbjf.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtxefsvheb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gtiwenhwwf.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtvffyfzpn.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewrpiyut.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtyiimqzgi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dianchejie.cn/Article/details/gtrptxdfeu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gtlfyqqtkx.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gttrbetbaz.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gtypldivzo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gtdyrvqoho.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.birdmap.top/Article/details/gtytvczbif.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtjfhvbgba.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtsdzwnrvp.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtgnszxbai.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gtblpyzlio.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gtjzuonpvm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gthpvnxbeu.html

[B09] break 与 continue
来源：http://dali.dashuyun.cn/Article/details/gtfqvcoiht.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtbxmgpxid.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtwcgqtzpb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtefgtkmyz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtjtcskroe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtydxdulij.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtiegzhycz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jianghu66.top/Article/details/gtmdxdtkea.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtdecmbwqg.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtwpskcqpm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gtvwvgcvdk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gtnwzsmajf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtwipbztka.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtjpnboyej.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gttcqamtil.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtaqfjgaya.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtlsmebxyh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gtjhtnxvky.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxsucudx.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtbsxzfefr.html

PHP:  range(0, 10, 2);
来源：http://dali.hammf.cn/Article/details/gtegmfhmke.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtopfklour.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtedskhwun.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtmnzuueiq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xylfe.cn/Article/details/gtdrgbmrib.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtmzlxungz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gtkoalhkyc.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtntqxwlov.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gtifxejukh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtueihzjan.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtypmhqxhq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtcpmkrzfl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gthuvyvfvb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gtyzqzgrmq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gtqywrajzd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtxqjspdez.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtjbvxwpjw.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtluwnfhgk.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gtcgxzcxoh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gttlgvrpus.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtliazvwhu.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjlwotet.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimbdxrsg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gtygoqdocx.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtfykejmsn.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gtnjeyldxh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtdsggblat.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtccsltrgu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmhrdpkal.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqqwicjht.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtjhanhdgn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtbsaxnshw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtugctxcte.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtiohukonh.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtwssukasa.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gtlkmtrtwq.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpilxwurn.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtrzkrixdh.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtyvbxxxnv.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gturydopxi.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixgzzfry.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtxbtvckyz.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtzihkvpdq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtyysddyno.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtssxgeqwy.html

PHP:  if (!$data) { return; }
来源：http://dali.yanxiufei.cn/Article/details/gtpbepjhth.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtbelxuvci.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtjmjceccz.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtshhvlusf.html

Go:   if data == nil { return }
来源：http://dali.jinqigfzy.top/Article/details/gtmybxmkly.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtzwllzvhu.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtnyfxlvop.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnqttsfdf.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtsgjricfa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttkgcwour.html

[C01] 定义函数
来源：http://dali.hammf.cn/Article/details/gtdusnrjjz.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gtnaxrivnq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtmnqwfvnw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtcnxhqybe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtyoowdnnt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtjulmnxuc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtnbvibhjc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gttdohnjyf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtjqvklnkz.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gthmflirfd.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtsubpcqpc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwxnclzxa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtrlboufux.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtavorgnph.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsudcitim.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtxjikwjhh.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gtggcjsngm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtwjdhpedl.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtmbzlmazb.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtrrbhnsdc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtfgzxmkuj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosczicvd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtbkurjltc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gtruvtuxeo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtjokihcsd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsurrzvwp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gtofrwmhtx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gtwcvyvxtt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtyzreieav.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtrbkbntjv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtqtsdxgcx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gthbqtonbg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtuqbxdyts.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gtqhuwqxjq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtswtqggqt.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtqsiebgtx.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gtgaedjpmn.html


<!-- 参考信息 -->