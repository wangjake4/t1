代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtjbtvgzgh.html

TS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtmmvjrzvd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhiwuduotai.top/Article/details/gtenuycoks.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgfzy.top/Article/details/gtsllaxnad.html

Ruby: value = data || "默认值"
来源：http://dali.yj202588.top/Article/details/gtpdkwovgg.html

C#:   var value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtpomzpsmn.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gtxmmjodjb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shuidangran.top/Article/details/gtdmklpqau.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenjidiqi.icu/Article/details/gtahfpdhag.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sysykeji.top/Article/details/gthxsjkzgz.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtekhmsirj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnqzz.top/Article/details/gtmnmrpowe.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tian-w.cn/Article/details/gtkmoowise.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtcwkljyav.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yueranfly.top/Article/details/gtckhbczxl.html

[A17] 位运算
来源：http://dali.xinyue.icu/Article/details/gtmcalwhax.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtlvopadff.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtzgdhuppd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtbgfcnapi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtoygenhjm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtoejtlltn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtgpxvzfdr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtwwotxjce.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtbrahldrt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gtqfxffhtn.html

Py:   ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtfgyyotja.html

PHP:  ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtpyyyyyyw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yangfankeji.com/Article/details/gttkefwrwt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gtbvbwjwdh.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gttmvyqjln.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gtigkflgbn.html

Ruby: "A".ord; 65.chr
来源：http://dali.jiagoushi.top/Article/details/gtgfjxxzth.html

C#:   (int)'A'; (char)65
来源：http://dali.haohaochexian.top/Article/details/gtnjsrzboc.html

[A19] 交换两个变量
来源：http://dali.hfpthk.cn/Article/details/gtiwhkwugh.html

Py:   a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gtzakyfpzc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlrriixq.html

JS:   [a, b] = [b, a];
来源：http://dali.wangshuangyany.cn/Article/details/gtlzautvdi.html

TS:   [a, b] = [b, a];
来源：http://dali.hnqzz.top/Article/details/gtoqglmufi.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtkiotczbr.html

Go:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtjnkxniqk.html

Ruby: a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gtdxgxuzvx.html

C#:   (a, b) = (b, a);
来源：http://dali.wangshuangyany.cn/Article/details/gthnwzvmsn.html

[A20] 读取标准输入
来源：http://dali.yonumen.top/Article/details/gtlcizcucv.html

Py:   name = input("请输入：")
来源：http://dali.wangdashe.top/Article/details/gtumhzngta.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuxming.cn/Article/details/gtggdzjybd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ydzc1.top/Article/details/gtmysgdpcb.html

TS:   // Node.js：readline 模块
来源：http://dali.redwolf501.top/Article/details/gtgymnveqb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xuetiantiany.cn/Article/details/gtcqsffhzf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gtohgmicai.html

Ruby: gets.chomp
来源：http://dali.hnxiangtu.top/Article/details/gtyheunbjg.html

C#:   Console.ReadLine();
来源：http://dali.sxryk.cn/Article/details/gtywwugaby.html

[A21] 保留指定小数位输出
来源：http://dali.pycfn.com/Article/details/gtlncqgyay.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangdashe.top/Article/details/gtvbfrxvjn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gtdofngedi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtborcgifw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtqixdjnbh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtivpketfp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gttuboqkzd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtvabqkfbk.html

C#:   3.14159.ToString("F2")
来源：http://dali.ydzc1.top/Article/details/gtbjycqfjm.html

[A22] 获取字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtuqkcclic.html

Py:   len(s)
来源：http://dali.jiagoushi.top/Article/details/gtrfzypann.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guannengcc.top/Article/details/gtasfywcsi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenzaomai.com/Article/details/gtqxcmcsga.html

TS:   s.length
来源：http://dali.yanxiufei.cn/Article/details/gtqqnvyxxh.html

Java: s.length()
来源：http://dali.hnqzz.top/Article/details/gtxaacagwj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.meibo888.top/Article/details/gtemjdhbkb.html

Ruby: s.length
来源：http://dali.9152youxi.cn/Article/details/gtkkurqure.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojlfdvqj.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtrfqnejwl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.guowangkeji.top/Article/details/gtymsurmqf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gtauaryznj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtccqtnvsb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtsahzekld.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejdmvyie.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cucudq.cn/Article/details/gtgpbtwgtv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtciketjqp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ivvv.top/Article/details/gtijhgvwyo.html

[A24] 去除首尾空白
来源：http://dali.nanxuanxn.top/Article/details/gtitvujguu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gtmecptgxa.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gtuapegniu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodylgqzp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gthnuyoakr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cashguo.top/Article/details/gtpnsqswah.html

Go:   strings.TrimSpace(s)
来源：http://dali.daxiang520.top/Article/details/gtbokhvgnc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ppjwa.cn/Article/details/gtzahnclxp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gtxkvbfbsr.html

[A25] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtufidecyw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dianchejie.cn/Article/details/gtnmyvsqbv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gtblkwjill.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gthdwxkggj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nwbrower.top/Article/details/gtspcyiqux.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtkssdhyac.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gtgjvkveqj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxwzyjqk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cdnleiting.top/Article/details/gtkurvlian.html

[A26] 类型转换总览
来源：http://dali.sufxvd.cn/Article/details/gtfogdejis.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtmiwzaqws.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigufen.top/Article/details/gtpehjemph.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhiwuduotai.top/Article/details/gtfylhrgqd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gtaqszbcdh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtxbvymrby.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.andypj.xyz/Article/details/gtpnufdrsf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gthcrmjvxj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtaxonjlke.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpjtcgmdq.html

B. 流程控制
来源：http://dali.zycfv.cn/Article/details/gtkcoibkhk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgigqctce.html

[B01] 条件判断 if / else
来源：http://dali.ppjwa.cn/Article/details/gtiwgjxqgz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gtszcfkgpx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.smart0.xyz/Article/details/gtceakupzn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtjlnmfujw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gthtratgnx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtikhrwrce.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xylfe.cn/Article/details/gtqkxjxqcl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gttywfcgjl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtqpmgxxlt.html

[B02] 多分支 else if / elif
来源：http://dali.zdqjudy.top/Article/details/gtdyzqyliv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gtamzdbgkt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gtwptxiuva.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtescklmta.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtcdulnyii.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtcyuzzvgw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yongpay.top/Article/details/gtnkxrzkem.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gtougorwvo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtyehiuyec.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gtiggilbuz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guowangkeji.top/Article/details/gtqbdnsmzf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtypkoxsga.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtbomxfrdr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtewpphpmj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpyanrkm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gtfxwrrmfu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shzxlz.cn/Article/details/gtopswuqpd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtrdsijovn.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtlceyvgtp.html

Py:   for i in range(10): print(i)
来源：http://dali.cdnleiting.top/Article/details/gthopcuufp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwajikotu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtencvxouw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtzofarsdl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.birdmap.top/Article/details/gtrovozaln.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtvbjfsbyx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gtzalkyvht.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuanzhike.top/Article/details/gtsezqgmwk.html

[B05] 遍历数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtpvxfzqny.html

Py:   for item in arr: print(item)
来源：http://dali.kuanghao11.cn/Article/details/gtlgcdiifi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.andypj.xyz/Article/details/gtmgervmna.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtzezziqyc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gttrmviumt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgpypwhjj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gtpihxexqm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yanxiufei.cn/Article/details/gtynvrajpa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gtjetmxzxh.html

[B06] 遍历字典 / 对象
来源：http://dali.sufxvd.cn/Article/details/gtsouamryh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtjrhazvau.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gttoadqejt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtmleqwtcz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtvdpkuljk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.quarkkingdee.top/Article/details/gtqcqehsma.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shangyingyoupin.top/Article/details/gthrhktosy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gtnpqneywq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gtkmpbcokr.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtgbkaaplo.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gtuveuxwcl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cdnleiting.top/Article/details/gthutnyqzo.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtqttgrriy.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gteyisfkhw.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtsbuqejdf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtkmxvwtsh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gtgyctvuoq.html

C#:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtjxibuwxm.html

[B08] do-while（至少执行一次）
来源：http://dali.yongpay.top/Article/details/gtbszchpgi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtgkeupxps.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.meibo888.top/Article/details/gtsyqrvksc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtxfhimyed.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gteuupwrmo.html

Java: do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtfkddraux.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gticpnslzx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hfpthk.cn/Article/details/gtfwlebamc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtbytouyxg.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gtukflknyi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cucudq.cn/Article/details/gtmfxbuefv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtousxbcjf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtkhxlfmps.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtldckkarm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtdbucedba.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gtqpmjmtcp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gogol.net.cn/Article/details/gtevdmxdmh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtazdgxarc.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtqnxfzrbl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gtchxwiqcu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugpjfdcb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtiimeqxmd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtjjcrczkc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aizwys.cn/Article/details/gtyvbonwox.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gtlrbyllns.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbjebdjh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtvyukcpea.html

[B11] 生成数字序列 / 区间
来源：http://dali.fengsongda.top/Article/details/gtuvqvenqw.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gtwxixcuae.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtxqgmqwoc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtkuzpyorz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtiqshhdix.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtlodztkxx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gtywqgdbzp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtnunhdcdx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daria6918.cn/Article/details/gttwieoexw.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtkptivbri.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtdpfcgphe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcvyplos.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtxeoulsfe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtbrjfphwa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtudjqzfoz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gtxhqjsqot.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gtvjiuclxs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtgfmcckax.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtdcpeddav.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gtpfngqutu.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtowpspbov.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtrajlkxhi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtnckbtssu.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gtqzzlzqxj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtrgzmtzyp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gtszcubxei.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gticwbebwf.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gtmikgsekb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtzfnfddaq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtzjmpwgva.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtgjiatcoh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtelzqzrxv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtedubpdsu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gtyvfsmjwf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gtgudvtuls.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtglwcitie.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtkmowbcwt.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtwwpoytyg.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gttghbrgmr.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrtspelx.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gttplkwumf.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfknhongq.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtvhcyvnes.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtfnzksypq.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtlsbnunrh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gtmnbsifoy.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtsvadppje.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gtgnymynia.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtiwdqltcv.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtuicozedw.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gthccisaxu.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtwfzgefay.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gttrtotsvf.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtxrdtqwyl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gteaeratxf.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtdligesot.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwkvsgxbh.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtchvjvfvs.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gthsviblkw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtolwbqgiy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtcorvpcvh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtbdzjoyhy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtbeoxffzc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtpmvbqwha.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gtjqllzffw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtugfktrah.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtjkplqqpk.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtqwxtihpd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtzzkqbkkr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdvijoiss.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtqjuybqow.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gtygzfpyxh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.mhx1999.top/Article/details/gtgexogatj.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gttawpzskr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtufrrvalj.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gthrryaeqa.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtcvssoefz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtbsjzoxyj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtgpmjekcr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtvyrcsqzx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxnfeopav.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gthmzwgoxk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtjkofyhxj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtgtfgbaly.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtitrdtoaf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtpfpdgmqu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtpwbnprjf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtlsrbstjh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gttffreici.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gtzzpvvzeg.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtwseurffm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtepgpxmfb.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gteinvpucr.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtvlvzxmwo.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtyczrvwxq.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gtewzniuhd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhwuxplm.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtzaxvnidl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gttefpqvxl.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtwlbdqzoj.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gtrdyisbpv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtlpvclysy.html


<!-- 参考信息 -->