代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtgqcqsixw.html

TS:   const value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtuuthrcrp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.bjfxy.top/Article/details/gtpiddoqhv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gogol.net.cn/Article/details/gtocahbzzu.html

Ruby: value = data || "默认值"
来源：http://dali.dashuyun.cn/Article/details/gtpkoglslh.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtzlyefyvt.html

[A16] 真假值判断规则
来源：http://dali.iojbl.cn/Article/details/gthqnygnuc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.guannengcc.top/Article/details/gtcfvujxqo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinghuilouyu.cn/Article/details/gtikqpcqbr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sweek.top/Article/details/gtvspsqese.html

TS:   if (!x) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlitudtbt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ppjwa.cn/Article/details/gtqwzlgeru.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.mhx1999.top/Article/details/gtocedpkjr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxuanxn.top/Article/details/gtstsojyqq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.havefunace.top/Article/details/gtiogyxyfq.html

[A17] 位运算
来源：http://dali.tian-w.cn/Article/details/gtbtingtjb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtcsbvqukx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cqqwz.cn/Article/details/gthjattfyt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtubzapeau.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtvjjzgsdl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtwbtxzzgd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtnrwkdmib.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtoomfcaui.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtpcyskmah.html

[A18] 字符与 ASCII 码互转
来源：http://dali.vqdsnc.cn/Article/details/gtsoavarsa.html

Py:   ord("A"); chr(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwzledke.html

PHP:  ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gtexqzonmo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gaohongyu789.top/Article/details/gtpdnmrwrm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gtgliywhkk.html

Java: (int) 'A'; (char) 65
来源：http://dali.316326.xyz/Article/details/gtapsuckse.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gtvablmwcr.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtyridulct.html

C#:   (int)'A'; (char)65
来源：http://dali.tianlin.xyz/Article/details/gturweaelc.html

[A19] 交换两个变量
来源：http://dali.xinyue.icu/Article/details/gtnglelrla.html

Py:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtsagpilhe.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tian-w.cn/Article/details/gtjczzvqhm.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gtacotataz.html

TS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gtkiyummtw.html

Java: int t = a; a = b; b = t;
来源：http://dali.xylfe.cn/Article/details/gtpapxqylu.html

Go:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gtoohtgswl.html

Ruby: a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtprlezujc.html

C#:   (a, b) = (b, a);
来源：http://dali.sufxvd.cn/Article/details/gtiatlyolx.html

[A20] 读取标准输入
来源：http://dali.shzxlz.cn/Article/details/gtsyqgmirn.html

Py:   name = input("请输入：")
来源：http://dali.cheryme.top/Article/details/gtuyebgqdb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenjidiqi.icu/Article/details/gttgzqrvbg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.haohaochexian.top/Article/details/gtjzcqqsmw.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gtbubrmbza.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtzcpuatyk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaijoebdg.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gtfkresuzg.html

C#:   Console.ReadLine();
来源：http://dali.dashuyun.cn/Article/details/gtvrluryha.html

[A21] 保留指定小数位输出
来源：http://dali.feifeiyinyue.top/Article/details/gtvmxtyxkt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.meibo888.top/Article/details/gtvgiqwojl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtxgegnhub.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtmkgkxcgb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtklzutwks.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtdtmydatd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtutxphwqg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtgusflqgf.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenzaomai.com/Article/details/gtytnjkrxj.html

[A22] 获取字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtkrzqhghu.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gtwscsxxbv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gthrgoiaur.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhoulong.xyz/Article/details/gtdkuhsriv.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gtpprhcfne.html

Java: s.length()
来源：http://dali.redwolf501.top/Article/details/gtmscufxom.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.iojbl.cn/Article/details/gtekqzesxk.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gtefttbuuv.html

C#:   s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtqibwgguh.html

[A23] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtopxuyfor.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.iojbl.cn/Article/details/gtcfdhedff.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gthrtuzaib.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtvzqxevrz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtrbcvgoim.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopafpxtj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqkkqtjp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtawtqotlr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpqrexyz.html

[A24] 去除首尾空白
来源：http://dali.xylfe.cn/Article/details/gtytovgtrv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shzxlz.cn/Article/details/gtocmvofkl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gtsyhwdexh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtjesbagbc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynxvdfij.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hammf.cn/Article/details/gtyisqmpcf.html

Go:   strings.TrimSpace(s)
来源：http://dali.0kj1m.cn/Article/details/gtokwomxkz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.quarkkingdee.top/Article/details/gtdxlmrqjp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtxgdaqrkr.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtiavuvqum.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cheryme.top/Article/details/gtzrognsar.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.c1oappe.top/Article/details/gtnplgctws.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gtavjddvev.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtmtndpdpe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gtvoylyhsj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gtmtgvtghy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.mhx1999.top/Article/details/gthtulpqnf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gtffzxqcen.html

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gtitlwpdby.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nwbrower.top/Article/details/gtvpazntdz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gtbtsyshrv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.316326.xyz/Article/details/gtbzbcrxji.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtjgojffkz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gteercilpe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yongpay.top/Article/details/gtwdrghegg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jiagoushi.top/Article/details/gtcfqupfvu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtpjalqiin.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gticzcugor.html

B. 流程控制
来源：http://dali.mhx1999.top/Article/details/gtcurxednl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxgoetnrs.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtjlkesyjo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuanzhike.top/Article/details/gtmdyutvfy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gtbryhbrdp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtlmxtqyjl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtammqwlwp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtfvkyuhgn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hywenlv.cn/Article/details/gtdyldhhhe.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guannengcc.top/Article/details/gtbbxusekm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtrkcawlxu.html

[B02] 多分支 else if / elif
来源：http://dali.shangyingyoupin.top/Article/details/gtpeamjyqz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.havefunace.top/Article/details/gthspvyblb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtvvsgrfjn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtupcfmggl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtwcjyjotq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtgxjjswhq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtbtwzrtvz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gtczpemhcs.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gttpspmxcz.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gtutdiehqu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gttqrexypr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtgvhqahmh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtuwwgssfh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtamcqnbvl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtrnguuhim.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtejwvsvwl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gttgbacncn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gtpfdqepgn.html

[B04] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtijxutuwg.html

Py:   for i in range(10): print(i)
来源：http://dali.nwbrower.top/Article/details/gtwxalhzzr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yanxiufei.cn/Article/details/gtgvvcnrnz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gthwlnzpag.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtyxylgabh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shuidangran.top/Article/details/gtixczmkaa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gtwhjapzwj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gtewrqhibu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtwsvjfbyy.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtbzereloz.html

Py:   for item in arr: print(item)
来源：http://dali.guowangkeji.top/Article/details/gtchikaalh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.9152youxi.cn/Article/details/gturiqrlfb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gtyhyannph.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtfvwgezyw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gthtpyomaj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqjjtkkn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tian-w.cn/Article/details/gtziqdddij.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gtooucloha.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gtqpwgjugd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zycfv.cn/Article/details/gtwgauhxuy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gtfmbnnxam.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gttvvjdfqd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtdpgwaxrk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtjbcvemmk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guowangkeji.top/Article/details/gtwstpgkzm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtgcsvsdvm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtokqwtfge.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtbkzgixlp.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gtsagilnwc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtuuejpnih.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtzejmqkoo.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtyeilahiz.html

Java: while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbwizmlby.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gtgppzyked.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gtsdkxuzgg.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnojzexsl.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gtqurfenvn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtokmnmruv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtdyyuoxfn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtizpybpvw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtbplfsjbu.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtondqluxh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtykbtnqgo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gtajemuxyv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzszftvi.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gtshmxcjig.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtuaniovgn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtykwspmnb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtxvlwwqwl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtivqwmoqc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtwbgstbcd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtzuccljcz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sxryk.cn/Article/details/gtwgiswfmf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtjpwolcdh.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gtxqthvsyf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gthwunztbj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtrgnobqaw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtpafvgkqk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gthoferrqd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gtxpaqnpof.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gttlumkxbf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gtoclydbli.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cdnleiting.top/Article/details/gtslmfdrdd.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtavbnauuj.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtynufflrz.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtnstknrry.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtoxkjscis.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtqqbrxquu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gtrqotzaiy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gtijbvhlvj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gtmeapibdt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtoggtjbuk.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gtulyrsjrv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gtpygygjfm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gtgqjdjeze.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtqmblvqsx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtfsvjhzvz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtuememjbu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gtgotkaour.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gtljbivqzo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtttrlfnkh.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtzfvxxmtq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtuncwglmh.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtnrisrzdx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjyjkwtcj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtkxxyrjel.html

Java: x instanceof Number
来源：http://dali.fzhhl.top/Article/details/gtkgkhkiui.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gtuwpunhel.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtucwvmdjk.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gtbefewyqi.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gteyykhyws.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtebfuyvwe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gtaakxoxcr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtkhnsdwwo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtnlcpxymr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gttkumvolr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtanjhheub.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtuabsdamt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtwtxtibmz.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gtgsvysjyk.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gtsxcpjoqc.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gtofyogjld.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtehsrrkdj.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtmuqmuqmg.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtcegvdfmg.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtxwxggxgv.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtywlmhavl.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtegrdhdsn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtumnhkbkr.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtnasgaqcn.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtwhjdcuxq.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtzmqgzgwx.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdebcpobo.html

Java: if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtpghhmbqq.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gtannfsqio.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtmsmonwfa.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gteivvsnnz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwobfwowu.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtpinaahrn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtziwhnykz.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtjulsofta.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtwjzljjsh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtbortskdp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtmduvzsbt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtigugtnoh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtapwbejrk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtjwerrsmw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtedpggoqx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtdcxjtrip.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtubjwfosw.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthucozpfe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gtnmpwqcmk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwvaujwky.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtnyyxggha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtmcecwwmh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtvuvhdarv.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtwnrmmnav.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gtlzeujnvi.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gtlotsmhzv.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtwcdgehtp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtmrjemgdh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtmzhbbmsa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtdnsjzbii.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtosoetpkh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtapskgfjo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtqimpmyrd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtllscqhto.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gttyoascuy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtiiwtoola.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtnarmfnxi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtdlovhoxn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoovwhuvv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gtchyoqatr.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtbzlcfgpr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtwdqkgdow.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtnzifznps.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gtcfudkbvn.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtqpcnnwze.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtwcbovrqb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtertazqxk.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtxaaxhsxc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtogcbcbog.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gtnsxvzmgz.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gtcgzhsdhs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gtlaslqiir.html


<!-- 参考信息 -->