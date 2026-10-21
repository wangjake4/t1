代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtzwwgiubi.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxncskwo.html

Py:   value = data or "默认值"
来源：http://dali.sweek.top/Article/details/gtszdgleux.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtpetklliq.html

JS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtoynlpefm.html

TS:   const value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtjrqmwejz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daria6918.cn/Article/details/gtccasrmcj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sysykeji.top/Article/details/gtwcpoiays.html

Ruby: value = data || "默认值"
来源：http://dali.yj202588.top/Article/details/gtnhtazqaf.html

C#:   var value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gtdfxfbpvo.html

[A16] 真假值判断规则
来源：http://dali.bjfxy.top/Article/details/gtqxvjwsto.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.c1oappe.top/Article/details/gtmzhaqbjm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.guowangkeji.top/Article/details/gtrszqwzvj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jyoumei.cn/Article/details/gtundbreeo.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjjesjhc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrixfvxeq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.mhx1999.top/Article/details/gtfcxqopty.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.bjfxy.top/Article/details/gtlwyfsqwe.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxkddxgps.html

[A17] 位运算
来源：http://dali.shuidangran.top/Article/details/gtwacgqcot.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtefashllz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhixingplan.top/Article/details/gteneyzbij.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgzucofw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtvusenqrb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gttsvfkefp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjykerkxp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtmdhytcaw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtmyrmooxg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gtcfkcqagw.html

Py:   ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmtmhrwm.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtpiekyjbx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gtqfqyyrnm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gtysugnups.html

Java: (int) 'A'; (char) 65
来源：http://dali.kuanghao11.cn/Article/details/gtyuxvstdj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.vqdsnc.cn/Article/details/gtvyewvkfr.html

Ruby: "A".ord; 65.chr
来源：http://dali.xylfe.cn/Article/details/gtnkltyeiu.html

C#:   (int)'A'; (char)65
来源：http://dali.ydzc1.top/Article/details/gtibznfujo.html

[A19] 交换两个变量
来源：http://dali.jqgfzy.top/Article/details/gtpsucmobp.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtojjtzmva.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sufxvd.cn/Article/details/gtrmbvvifq.html

JS:   [a, b] = [b, a];
来源：http://dali.vqdsnc.cn/Article/details/gtxurlsrzw.html

TS:   [a, b] = [b, a];
来源：http://dali.hnxiangtu.top/Article/details/gthtohhbav.html

Java: int t = a; a = b; b = t;
来源：http://dali.havefunace.top/Article/details/gtjqjbodkd.html

Go:   a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtwtyondxl.html

Ruby: a, b = b, a
来源：http://dali.yongpay.top/Article/details/gtykarxtrx.html

C#:   (a, b) = (b, a);
来源：http://dali.xziqi.cn/Article/details/gtwnabjyyk.html

[A20] 读取标准输入
来源：http://dali.hnqzz.top/Article/details/gtuthsnwzr.html

Py:   name = input("请输入：")
来源：http://dali.yueranfly.top/Article/details/gtfekburoa.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhixingplan.top/Article/details/gthxptgnum.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nwbrower.top/Article/details/gtibhnpyzp.html

TS:   // Node.js：readline 模块
来源：http://dali.hnqzz.top/Article/details/gtpmwjuwus.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hysaishi.cn/Article/details/gtldmpqzsf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aibaodan.cn/Article/details/gtikvcqaic.html

Ruby: gets.chomp
来源：http://dali.tianlin.xyz/Article/details/gtljkpngji.html

C#:   Console.ReadLine();
来源：http://dali.pengpengdd.cyou/Article/details/gtbdmsqyxs.html

[A21] 保留指定小数位输出
来源：http://dali.chenjidiqi.icu/Article/details/gtxysvbzzy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuanzx.com/Article/details/gtbglmigaz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gtvmnuaxhe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtbllhwfip.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtgnovqzsf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gthkvvpzwk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtdsbrrybh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gthzwqhnbw.html

C#:   3.14159.ToString("F2")
来源：http://dali.tian-w.cn/Article/details/gtykhrdtih.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gtzzubqtge.html

Py:   len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiiucqbh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gtwckymwxt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.quarkkingdee.top/Article/details/gtltxhcpub.html

TS:   s.length
来源：http://dali.aibaodan.cn/Article/details/gtnmgaqshw.html

Java: s.length()
来源：http://dali.sysykeji.top/Article/details/gtbtciuqob.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtoaoadruk.html

Ruby: s.length
来源：http://dali.gzhubu.top/Article/details/gtzwrdrmhj.html

C#:   s.Length
来源：http://dali.316326.xyz/Article/details/gtfluedkta.html

[A23] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtpgqffnde.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yueranfly.top/Article/details/gtpwjxhtgy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daria6918.cn/Article/details/gtzlssjejo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gttraygaja.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtdgdmfstx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gtnmisuoqj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shzxlz.cn/Article/details/gtakbujcyp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtpbfxgwkl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yvedp.cn/Article/details/gtlklhapdb.html

[A24] 去除首尾空白
来源：http://dali.daxiang520.top/Article/details/gtcrkhsjuq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhjathfl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangtech.top/Article/details/gteiuaryvk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklztrrjh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtcfnmsfzf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258888.top/Article/details/gtjozovfwa.html

Go:   strings.TrimSpace(s)
来源：http://dali.hammf.cn/Article/details/gtxiitayyj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gthrlkxtma.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtngnhhzzv.html

[A25] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtghncctyn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gtdopfckpt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsuemysu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtarmgkffc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gtbfknqvwp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gtdizfqmys.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtwxhkkgvm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tian-w.cn/Article/details/gtztkbhxya.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gtuiyjcoas.html

[A26] 类型转换总览
来源：http://dali.xylfe.cn/Article/details/gtwryazpqm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtsvwyuppu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258.top/Article/details/gtagowamyp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shangyingyoupin.top/Article/details/gtikttxvsh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258.top/Article/details/gtmmjmkvrq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gtdnwcsjqm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gtmnvcwrul.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gttfpnihvb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gthptalxmc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhweijcz.html

B. 流程控制
来源：http://dali.daxiang520.top/Article/details/gtsolbwsms.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwbnhradx.html

[B01] 条件判断 if / else
来源：http://dali.ehwqpu.com/Article/details/gtpmtuqtjg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gzhubu.top/Article/details/gtyzgttugo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tanke756.top/Article/details/gtnbiqbxxo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gthxrfzlez.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gthyvhwdyg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtzhdfydpw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gtmozbznbw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsrfktzl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtjdnecrte.html

[B02] 多分支 else if / elif
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfbncvny.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtetasstlj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgufenzy.top/Article/details/gtkdpmkvra.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gttuxsirqr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtbsrcmugb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtpnzvukju.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fzhhl.top/Article/details/gtewwhsvby.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gtrpitembf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtkmwgpocm.html

[B03] switch / match / case
来源：http://dali.jyoumei.cn/Article/details/gtfaionfwo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gtnfbycqqw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtgqevhnre.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktfubeie.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtmhoiaory.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtdibsnvhv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtookmvpap.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuanzhike.top/Article/details/gtnfuvzlrh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtkcikdocg.html

[B04] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtqidzkivk.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gtusldnszn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnqzz.top/Article/details/gtagdmqulu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gtqjhjxesz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtijwtrusn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ppjwa.cn/Article/details/gtwogdpavi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gthuitlnol.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sweek.top/Article/details/gtkucfkbaa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gteiohlgyw.html

[B05] 遍历数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtmxacafwt.html

Py:   for item in arr: print(item)
来源：http://dali.quarkkingdee.top/Article/details/gtscytabkb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fengsongda.top/Article/details/gtpbceogvd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gtukojcnzh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtuispiwky.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtpfieguwe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.haohaochexian.top/Article/details/gtpnpafvxb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangdashe.top/Article/details/gtpkdrdwmf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gtjklsnuyk.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gtrdewteac.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigufen.top/Article/details/gtzrvuseij.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cucudq.cn/Article/details/gtnagcxsql.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gtlvndwepn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gtpeettwch.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gtdpyqehzw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.0kj1m.cn/Article/details/gtmmoyrxtf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenlongwang.top/Article/details/gtqemimylv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgoptvgw.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gttuwqeuuy.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxkaqmof.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gtypxqsaxm.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtqristzcv.html

TS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtkgwumdab.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtamhnvlvb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gtaulupdpm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gtoonglbfq.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtnqiyqmnn.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgufenzy.top/Article/details/gtbzovrjyw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtjmnceohv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtvthtamlx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtztotkfig.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gthehtquop.html

Java: do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbflghlpu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gtrqvwowcg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gtmyugekts.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtsaizhunp.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtupwhwiza.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gtsiygbgwc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtbywscodi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtlwsmlwoh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gttjprhzgs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtkmuanwyp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtdhjissxa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gteplfokim.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtszcomvim.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gteqjlfzhd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gtafwjdtwu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gtctmqfhpg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtsoqxqxqz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gtvliklmqk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gtlhfdkqjc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gtbiixsosy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtvioeivrx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gthysnzepz.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtfewbmmvi.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtuvuglaxg.html

PHP:  range(0, 10, 2);
来源：http://dali.meibo888.top/Article/details/gtotfiazui.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsrszimr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtygmgiyav.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzlkjyvb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtqwjngwhr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daxiang520.top/Article/details/gthkweosgo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtzabahkcu.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gtqlmrthha.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtihnvbtcb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gtoixydpmr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gttmkqantd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtqpgrovvu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtblcvftnm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtisyeyncx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpetgfkvx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gtlkffzgww.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtsfshgsaq.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtkyidmaic.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtaghtubzq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtrbhmqzdo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtcddiursr.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gtbqfjlill.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtxzhjcedo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gtalvzbonc.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtbwbcjdkl.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gtyfijjpln.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gtqnbloogx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlgicywm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtphwbagzj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtrbolskku.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtjdmccoru.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gttkqjrzrf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxsjobctm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtswekdavp.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gtaxwceudz.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gtcwfafrne.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtbblojxzz.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtddwddxfk.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtowvcgbdl.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtgwpgvycm.html

Go:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtycjtidbe.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtaimvfutz.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtrhyarcfj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtetnlzgpu.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gtoeaslnzh.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtmovyoelp.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtebnryfmn.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtewdxmaxb.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtbaroykfu.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtjtgtvkmf.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtiiiiwiqp.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkbfhqzj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfhpvzwac.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtkwxfgbjl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbmdetbng.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtomoryzmt.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtqutnlzjf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtmmahibhc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtwzkhusjp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtshcodcei.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtnprhknke.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtyofewckd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gttpeccbsz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtjddfyymj.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtscdjndws.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtcihlepuy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gteyaymasj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gttvhasynz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtwwkqcuio.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtmbprnbgg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtqemhwhqu.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtlpuglmys.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtgnvvagsc.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtardtitwh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtnxrmgjab.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gtbzqpobkc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtmgnkfupq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtwndiwcyp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gthgpxewap.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtynyctgub.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtjrpqffzo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtdkjiggxr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtaqrlwacf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtmepyplmg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtnoqrrnsj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtuzbundaw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtblzveqzn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtssgwolpf.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gtkjkndvsy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtfwvcuizd.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtukusiwae.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gtwnlcldkt.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtopvumbwi.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtbttfjwzu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtgvnsxacj.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtwegiphyd.html


<!-- 参考信息 -->