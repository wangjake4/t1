代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.zhengqikj.top/Article/details/gtnwkoults.html

C#:   var value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gtdphmnwtk.html

[A16] 真假值判断规则
来源：http://dali.hnxiangtu.top/Article/details/gtauujdgtn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ehwqpu.com/Article/details/gtjlbrhfug.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.feifeiyinyue.top/Article/details/gtpiiworth.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.0kj1m.cn/Article/details/gtkwrwfrom.html

TS:   if (!x) {}
来源：http://dali.nanxinkj.top/Article/details/gtkrtpwjex.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotmzewcz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgfzy.top/Article/details/gtmywhvbts.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hfpthk.cn/Article/details/gtnhnosmfa.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daria6918.cn/Article/details/gtorexfhax.html

[A17] 位运算
来源：http://dali.jlsjyb.cn/Article/details/gtpawlqnrr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtsyohvobl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtzdlamxsm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtpoyvsspl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtrgjsqhoc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gttvfycvsq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtctpqraft.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtsuluqfed.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtnjpuplnz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhongyouzk.top/Article/details/gtrkuyfdix.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gttgimqnwp.html

PHP:  ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gtlsaynixd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtbuecafyq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtsdvokege.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gtuacabuet.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ybcxt.top/Article/details/gtdamgmiev.html

Ruby: "A".ord; 65.chr
来源：http://dali.yanxiufei.cn/Article/details/gtebpgcsci.html

C#:   (int)'A'; (char)65
来源：http://dali.c1oappe.top/Article/details/gtoctgwugp.html

[A19] 交换两个变量
来源：http://dali.c1oappe.top/Article/details/gtsrimpbrj.html

Py:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gtadgkvigr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gtpzshzxlk.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gtyahvtdqs.html

TS:   [a, b] = [b, a];
来源：http://dali.hfpthk.cn/Article/details/gtyocuzllo.html

Java: int t = a; a = b; b = t;
来源：http://dali.tianlin.xyz/Article/details/gtrdiebzhb.html

Go:   a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwnilurf.html

Ruby: a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtjnwuezre.html

C#:   (a, b) = (b, a);
来源：http://dali.cheryme.top/Article/details/gtirfbxvqg.html

[A20] 读取标准输入
来源：http://dali.zhoulong.xyz/Article/details/gtimpkqsbw.html

Py:   name = input("请输入：")
来源：http://dali.jianghu66.top/Article/details/gtdbjvcgfr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gtafapklsz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gtnqucnaxv.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxuanxn.top/Article/details/gtbdxytfim.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtxftwckcd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtxfofbz.html

Ruby: gets.chomp
来源：http://dali.mhx1999.top/Article/details/gtjabyumla.html

C#:   Console.ReadLine();
来源：http://dali.zhongyouzk.top/Article/details/gtuialpqzl.html

[A21] 保留指定小数位输出
来源：http://dali.gaohongyu789.top/Article/details/gtvhfogsjh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtiidupklr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtlelgtfev.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtijlqfvdv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gttabnfssz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtifbwvbtu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtcvloikas.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuuzsvvz.html

C#:   3.14159.ToString("F2")
来源：http://dali.bjfxy.top/Article/details/gtfptgxocw.html

[A22] 获取字符串长度
来源：http://dali.redwolf501.top/Article/details/gtjnwtulrf.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtwmiqhsvp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cdnleiting.top/Article/details/gtgiazwxia.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aizwys.cn/Article/details/gtggwcpcmf.html

TS:   s.length
来源：http://dali.haohaochexian.top/Article/details/gtkwzfpqut.html

Java: s.length()
来源：http://dali.snrcjt.cn/Article/details/gtxipyjysb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.smart0.xyz/Article/details/gttwrcdsog.html

Ruby: s.length
来源：http://dali.yongpay.top/Article/details/gtodpqcchy.html

C#:   s.Length
来源：http://dali.xinyue.icu/Article/details/gtpvwehlrl.html

[A23] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtzxxobluf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yongpay.top/Article/details/gtxzqdgsuv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtfpdgfeaf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtrsbhmisx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gtwaahwayj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtvugmygup.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jyoumei.cn/Article/details/gtpvoomwtx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtjnwfdggu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gtoopiwurh.html

[A24] 去除首尾空白
来源：http://dali.jinghuilouyu.cn/Article/details/gtixdpjtgt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenjidiqi.icu/Article/details/gtlaztgzbd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daxiang520.top/Article/details/gtdzqxwsth.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtfjnsfoty.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gteltcivye.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuanzhike.top/Article/details/gtteizqidd.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhixingplan.top/Article/details/gtppbrkrbc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuanzhike.top/Article/details/gtlfcdbczf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtaxlfjqbq.html

[A25] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtnzdbjhwd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gttqnayxyt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gtuccfatwu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtfnuureoi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtsoabzrrr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtomysikhq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gtbpaezgzg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtsinwzcwc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gthqfjewep.html

[A26] 类型转换总览
来源：http://dali.fzhhl.top/Article/details/gtividigbs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhoulong.xyz/Article/details/gtimzikcal.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jlsjyb.cn/Article/details/gtfjqdpegx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj202588.top/Article/details/gtuivyywsw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ywan-chungtsiang.top/Article/details/gttarhmshr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtfkfivdiv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtupyjekjb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gtygxltclv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtynbzrkxi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzkegxwoz.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gtviadqhop.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxslucihd.html

[B01] 条件判断 if / else
来源：http://dali.snrcjt.cn/Article/details/gtuhqyesih.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenlongwang.top/Article/details/gtrornlgus.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfldfbpmc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtdudmwcwh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtuzawdxzd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtdsifmahl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gtkehmsxuy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gttzomgnev.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtcpmubevc.html

[B02] 多分支 else if / elif
来源：http://dali.dianchejie.cn/Article/details/gtjblacaio.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gtlhtdrsyk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jiagoushi.top/Article/details/gtjhwsthcc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtgncmrpfc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtuwlqbfoh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtoxxikdac.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfghjnvjt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.9152youxi.cn/Article/details/gtseiaqbra.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gthebnbiiz.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtaeixbnwj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenzaomai.com/Article/details/gtcchtjraz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbixzkyxm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonlxbbdd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtvxavhweu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjudklwe.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtollnjixc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtzdhhkczr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtcutysvxf.html

[B04] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtxwazypli.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gtdrpfhshf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zdqjudy.top/Article/details/gtrcvygpkv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtfxapjarx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gtgjyufmbe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sufxvd.cn/Article/details/gtcjwbljpi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hywenlv.cn/Article/details/gtuewxmgsk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aibaodan.cn/Article/details/gtyothulmv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dianchejie.cn/Article/details/gtbnweukkw.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtryujsqxv.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangtech.top/Article/details/gttqoecpbl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gtlljmlrtq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhzfbxox.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gttchvoozg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gtifmfqkmn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtqvmlysit.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gtsfzopwdd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtoippchog.html

[B06] 遍历字典 / 对象
来源：http://dali.cucudq.cn/Article/details/gthacrobxh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yangfankeji.com/Article/details/gtxlvepmbq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yongpay.top/Article/details/gtenlcfbce.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtaolvgief.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtevgmkqwj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gtsoklwlik.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gtammxlzqs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gtywiajsvs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gttlemplan.html

[B07] while 循环
来源：http://dali.yvedp.cn/Article/details/gtgbauzars.html

Py:   while i < 10: i += 1
来源：http://dali.shuidangran.top/Article/details/gtojadpkyq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gttrtvkuuw.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtsxffqhzt.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtajbbfrsi.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtabupiegd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtdfjhmoue.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gtjijqofwt.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtqjhlumym.html

[B08] do-while（至少执行一次）
来源：http://dali.aizwys.cn/Article/details/gtepjcsfsh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcucoljw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gtulqbhknt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtmzzxugdi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtciihxcxm.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtcpekkifv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtfxieivfd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuetiantiany.cn/Article/details/gtsvpyibmz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtgtjmxfgf.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtshtyizmn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gtsyoajbad.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtzpbkwkrm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtptvbwlwv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtxesjcupb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtgshmlbml.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gtliismpcq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sweek.top/Article/details/gtknztczhf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtfegdjipq.html

[B10] 遍历同时拿索引
来源：http://dali.aibaodan.cn/Article/details/gtkoxokhic.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.0kj1m.cn/Article/details/gteuvbgfcg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszdpuiso.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtyhkpjedl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtwesvqvvf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnglufheb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqqapovf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtpdvfpxwa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuxming.cn/Article/details/gtemmzzgte.html

[B11] 生成数字序列 / 区间
来源：http://dali.316326.xyz/Article/details/gtugqnaozo.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gteeycoakn.html

PHP:  range(0, 10, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gthcozfdfr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtnryjqpmg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtwhjchjpj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gttoknwbeg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtzgqqqrgt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cheryme.top/Article/details/gtfljknimy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gtshuhfcko.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gtoacfnfjw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gtcoigaypc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtdmtxjyaw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtawqrwbrw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtzggaavcc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtsptypqxr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gtlfrlrimr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtjtkivufd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtffevsyhu.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtuppoxthj.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gtlieppbjf.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gtghsewoaw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtsfnsohlk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtvbhmzhny.html

Java: x instanceof Number
来源：http://dali.dashuyun.cn/Article/details/gtuyrlqakc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gtxoqjxelq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtvmwxdcyv.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtnpssogqr.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gtupuejxvn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gttfgkkrvp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtofwegxzf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtmbsbzvwg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtiejkdvyf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtwuypkpak.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gtksguttre.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtssoxaphg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgqmqtawn.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtgfbqtuve.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtfyreiadh.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtocawmoga.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtaeorsngs.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtzmwnmwwe.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtdglstyfu.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtwsjoxndm.html

Ruby: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtkinvsygn.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtolpowlbs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtwqfbzvjw.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtzbrntkuu.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtkcfehvor.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlckdmbtr.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gticsihser.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtvjgxrxzv.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtloitkokg.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gtzslonwry.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtgjcnitil.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtophzytbp.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtiivmollq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrvrscvei.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxzgmfqxc.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtwotmuwht.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtjcthhmic.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtdioheplt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtpbpfgrkj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtzjpisequ.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtllcqhnga.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtqdelllxa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtumojesgu.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtqgsrzhae.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwihfhqse.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtmagiyhpt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtginabost.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtkohkeack.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gttrmsfnnh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtirlcuqst.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gtqcnxsdoz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gtrczhagct.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtcubbmazp.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtqsnozqlu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gtnkwxfuji.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtvybltyax.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtlkrslada.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gtvacipsam.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgfeykyc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtalwzquhr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gtotubzftm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtqjxobsue.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtjufeyryc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzodhvzah.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gterutrsfz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtirjjhebl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gttpwjooaj.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcwbbzzp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtspmfulmq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtpuxitzcn.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gtboiblkxv.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtxvhuabmi.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtafvldpay.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtcoessspn.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtgeafmtna.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gttyuqanbl.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtbtjwytip.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtglqosnhe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gtxxzjbrog.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtgtggcnhh.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtysvpzzpd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtovxyfphp.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtqexarnqc.html


<!-- 参考信息 -->