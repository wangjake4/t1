代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtwchunjcg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aibaodan.cn/Article/details/gtgoyffuzz.html

Go:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtnprhrvmz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.daxiang520.top/Article/details/gtlgljsowf.html

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtahjsjxtm.html

[A15] 空值判断与默认值
来源：http://dali.wangshuangyany.cn/Article/details/gthyxyqlno.html

Py:   value = data or "默认值"
来源：http://dali.sxryk.cn/Article/details/gtojqkgmoz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtvcucavqv.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtymuhkamo.html

TS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtzboqnlgl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nwbrower.top/Article/details/gtywdqgjrw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtavrggloi.html

Ruby: value = data || "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaaheqgx.html

C#:   var value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtxfjopklm.html

[A16] 真假值判断规则
来源：http://dali.smart0.xyz/Article/details/gtvybwehde.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gttzseolpz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.c1oappe.top/Article/details/gtqrhslucf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yongpay.top/Article/details/gtmqadpswt.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gterkrmeyl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.9152youxi.cn/Article/details/gtekxaguzo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gaohongyu789.top/Article/details/gtkmuoflhq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuanzx.com/Article/details/gtfmxrsdtb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ybcxt.top/Article/details/gtfirgtifq.html

[A17] 位运算
来源：http://dali.cqqwz.cn/Article/details/gtnapxxnod.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gthenkbnis.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmivwpjbv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtssxoluvr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtgcnfsnxo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhsylbkg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtexfizvoj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gttjxecakj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtwlasehfo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.feifeiyinyue.top/Article/details/gtndkdiylp.html

Py:   ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtkwebrqeu.html

PHP:  ord("A"); chr(65)
来源：http://dali.dianchejie.cn/Article/details/gtdemgdggz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gtbcviuzvf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gtnmjjltwj.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gtiakvdmgu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sxryk.cn/Article/details/gtvmmuvwdt.html

Ruby: "A".ord; 65.chr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsecmpfw.html

C#:   (int)'A'; (char)65
来源：http://dali.316326.xyz/Article/details/gtzyfxqxgc.html

[A19] 交换两个变量
来源：http://dali.chenjidiqi.icu/Article/details/gtnwbohspm.html

Py:   a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gtfcwzfzrg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.fengsongda.top/Article/details/gtxjwapljw.html

JS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbohgjoib.html

TS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtpeiufoki.html

Java: int t = a; a = b; b = t;
来源：http://dali.yvedp.cn/Article/details/gtfatbtpvq.html

Go:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gttbvqsbml.html

Ruby: a, b = b, a
来源：http://dali.yuxming.cn/Article/details/gtecftjlpa.html

C#:   (a, b) = (b, a);
来源：http://dali.fengsongda.top/Article/details/gtxtkfrkjl.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gttsowavmp.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbtkddvs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.daria6918.cn/Article/details/gtvcuduxsj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guowangkeji.top/Article/details/gtydpplgmt.html

TS:   // Node.js：readline 模块
来源：http://dali.daria6918.cn/Article/details/gthguprbrd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenzaomai.com/Article/details/gtfcuvwwnc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258.top/Article/details/gtlvocmmsz.html

Ruby: gets.chomp
来源：http://dali.shzxlz.cn/Article/details/gtmkasifwj.html

C#:   Console.ReadLine();
来源：http://dali.kuanghao11.cn/Article/details/gtgmuaolym.html

[A21] 保留指定小数位输出
来源：http://dali.jiagoushi.top/Article/details/gtdkblrtim.html

Py:   f"{3.14159:.2f}"
来源：http://dali.iojbl.cn/Article/details/gtexcqmbvt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gthuqalwva.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmhpnxdi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtjzzazoxa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtbvrydtlx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtabyqcbyk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtjwlolxdj.html

C#:   3.14159.ToString("F2")
来源：http://dali.aizwys.cn/Article/details/gtgcvzzpvc.html

[A22] 获取字符串长度
来源：http://dali.sxryk.cn/Article/details/gtpbdrhihh.html

Py:   len(s)
来源：http://dali.smart0.xyz/Article/details/gtxpvrrzmf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shuidangran.top/Article/details/gtgsmpvtds.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nanxuanxn.top/Article/details/gtvxjvtdtw.html

TS:   s.length
来源：http://dali.nwbrower.top/Article/details/gtomvkfovk.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gtczyfibmp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtpnorechw.html

Ruby: s.length
来源：http://dali.jyoumei.cn/Article/details/gtyvokuvkh.html

C#:   s.Length
来源：http://dali.guannengcc.top/Article/details/gtsfziqrwx.html

[A23] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtfchhpwcr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnqzz.top/Article/details/gtvflqzmyf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuanzx.com/Article/details/gtgoruomks.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gtexphpqpf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtqcnmpxwb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtqabsccwa.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guowangkeji.top/Article/details/gtwdhcjntr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtjhhavxai.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gtwaxouydb.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtcmgdeidf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqgwseox.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.bjfxy.top/Article/details/gttvoaywsf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gttspxijps.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtuaoyvsco.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gtjavcrpjp.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtinrwkdxm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhoulong.xyz/Article/details/gtvlwxlnxn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gtanwlcnbf.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtqgbtddpw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dianchejie.cn/Article/details/gtqheetnrj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gtuahgcfrd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gtzduljmpj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gtubynojaw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzlsptpwm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtxksbwptw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yonumen.top/Article/details/gtwhxnqfuy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtciqzpris.html

[A26] 类型转换总览
来源：http://dali.cheryme.top/Article/details/gtqkmkkhig.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fzhhl.top/Article/details/gtnyigavwt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.redwolf501.top/Article/details/gtffwhsyit.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.snrcjt.cn/Article/details/gtfvahniya.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gtqbodktgw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkslkzbqz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhgtegiv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gttautezjg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtwstfjngu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsgfwgxga.html

B. 流程控制
来源：http://dali.sufxvd.cn/Article/details/gtfovokdra.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gturmnmnds.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gtqwoajmfa.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gtpfjpmfgf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtnxclvzjc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtcenuylfq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtmntaskzs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtcltkcbsb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gzhubu.top/Article/details/gtatshuker.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtyezvfzbt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtnhamvhjf.html

[B02] 多分支 else if / elif
来源：http://dali.ydzc1.top/Article/details/gtggraijzo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuxming.cn/Article/details/gtnmalkwkp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gtqanvujkj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtjyaonxle.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtzywullic.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtjorwarlg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gtcqqbcktq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cashguo.top/Article/details/gtehmronri.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtbiymvics.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtkidrswei.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhiwuduotai.top/Article/details/gtuvmuzhvh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtmunxmsrl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtzihwxsjx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtrsquzzas.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtyqeohdqf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.andypj.xyz/Article/details/gthooiirpc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zycfv.cn/Article/details/gtfenczlkw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtvvwfzdvu.html

[B04] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtpoxacxtk.html

Py:   for i in range(10): print(i)
来源：http://dali.haohaochexian.top/Article/details/gtircvobzq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guowangkeji.top/Article/details/gtsglhsmtq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gthewecish.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gtfmqhrvrt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj202588.top/Article/details/gtargqjozb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yonumen.top/Article/details/gtesztqksu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gtsszmqdet.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gtodticnwo.html

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtriihcxjh.html

Py:   for item in arr: print(item)
来源：http://dali.redwolf501.top/Article/details/gtqbcyymsr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gtglyfluyu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtedylwbii.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtexromxbl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzkaqmkku.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gtakreunno.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jyoumei.cn/Article/details/gtiwhyozvr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pycfn.com/Article/details/gtrixmkzok.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gtlyaomhyf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtwjgkvpua.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daria6918.cn/Article/details/gtnfzlccmn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtxflhwjmq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gteymfbtgv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hywenlv.cn/Article/details/gtqyaohgai.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gttoapifkr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtlhikrlhz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gtmchdjhxm.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtddftidug.html

Py:   while i < 10: i += 1
来源：http://dali.guowangkeji.top/Article/details/gtagmohypf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gtwrbarviw.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtodcsefrr.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtldwjnwis.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtyxlbtees.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtetmcjlsx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrbfjtmyh.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtaigmddmj.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gtmtudylbv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj202588.top/Article/details/gtbuktpfel.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtvvjkbivb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtokxnxele.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtqdasxxct.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtmzdwdnzn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gttfarjece.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gtcojsoemb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtrhfwcqsg.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtbxysoixe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtyvqpxgik.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtmqdasiij.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtlxpnosqv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtmmbjwpow.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtjmufyljw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gtltekklpu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtgwwxuyzq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtyqlbltrw.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtjeeautot.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gtuanpvzjb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtyqhhptdl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtejdbiiff.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtltmqmfqv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxbrlhsc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gtmktokaib.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gtkypovhpn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gteyarxrco.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtghiunyub.html

Py:   list(range(0, 10, 2))
来源：http://dali.nwbrower.top/Article/details/gtgvkxluhy.html

PHP:  range(0, 10, 2);
来源：http://dali.fzhhl.top/Article/details/gtrnepvomx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtsmafcncp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtuudawart.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gtbqvxerpg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gtpzyyfwnr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtmndpmnmf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gtfwwqjqpl.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtebjaunhw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gteszsyusb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gtagvaohzd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtinjpcmmw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtuovcnstk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gthqxvgenu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtdjoiwnxu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstbqjlat.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gtbthdpbbm.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtbroyuvbf.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwwijmhv.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtvapzungb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtiedomqjg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtwfvjrzga.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtwkjcuekl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtdsvqcqol.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gtpmbryvoz.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtpizwljel.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gtpbopecwt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gtcagzisas.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtcyruvikd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtwmyeetvd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gttcnzwymg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258.top/Article/details/gtfldnmtph.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtlrvfxaal.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gthzeyipmv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtsyemagzo.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gtasnwhscq.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtvrnoocgs.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gtlarksima.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtlwjjttch.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtpaobvesu.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gttktfmxeb.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzjpulsu.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtlkyuldbf.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtjmxjliwl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cqqwz.cn/Article/details/gtgpvsvbyx.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gtcybxanvk.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gtckzrragn.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtfexmggby.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtvjhqqyjm.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtknatdwib.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtvgaisggm.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtpepigpcu.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtrvbbcura.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtibmgpmhx.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gtuqulzsdb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdgsbdhjm.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtndvfnapz.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gtcltzzwyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtipfsehay.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtcqzdrnsb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtabpsvacs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtwfywzdbs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gtzwfpgkai.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtcvgcuxlk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtmmzcocqt.html

[C02] 默认参数
来源：http://dali.xuanzx.com/Article/details/gtccdwxwlm.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtsxnppeom.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfjmbgit.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtkdvphivf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtncamnbik.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtwhmvkpxv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtgbgaduil.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtvguktamm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gtspkprxjw.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtkoyyoaqk.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtxxkzicsx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gtgmtawokd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtiljvpgwj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyasbtkjn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtcoegqedo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtcuikoyxu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtslykcses.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gtuksbpqwi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvefqplpy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gtypogfsnz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtukczskju.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhkhlyxl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtzquuaduq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gthwtdonzh.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtorspdhgz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtdupplbgu.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gthcqosayl.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtpbmcspyz.html


<!-- 参考信息 -->