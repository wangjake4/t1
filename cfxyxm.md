代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtrfyscswe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.havefunace.top/Article/details/gtpwrhmtdo.html

Go:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtfbedefeo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cdnleiting.top/Article/details/gtvqegcutz.html

C#:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtwyhdjgox.html

[A15] 空值判断与默认值
来源：http://dali.smart0.xyz/Article/details/gtniryfedw.html

Py:   value = data or "默认值"
来源：http://dali.hnqzz.top/Article/details/gtksfhpicy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gttlqmrcxe.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtzrhizzum.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtqfduwkyf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yvedp.cn/Article/details/gtblbggqxb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gaohongyu789.top/Article/details/gtyndjqaqk.html

Ruby: value = data || "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphnzbnvc.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gtovrlvmfx.html

[A16] 真假值判断规则
来源：http://dali.jinqigfzy.top/Article/details/gtglnlbhlk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xylfe.cn/Article/details/gtxxyemjak.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gtdapvxien.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ivvv.top/Article/details/gtpqrkwaze.html

TS:   if (!x) {}
来源：http://dali.xinyue.icu/Article/details/gtseuqkgxf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuerovjgp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shuidangran.top/Article/details/gtjnjeosnv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gthhqexjur.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsizovopu.html

[A17] 位运算
来源：http://dali.jianghu66.top/Article/details/gthuwardkw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtdgcajryl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtlwjzeubd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtogwaovbp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gthnajarkf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtxigdvzak.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtwhslxbgc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtkbwarkkv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtyzkaakev.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gtltvxeawg.html

Py:   ord("A"); chr(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtfqkzkbwk.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gtnsarpvqc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gtjrhcdwcy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gtveddbqtr.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuanzx.com/Article/details/gtwfxylwbs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gtinlbexlu.html

Ruby: "A".ord; 65.chr
来源：http://dali.cqqwz.cn/Article/details/gtmlekexzb.html

C#:   (int)'A'; (char)65
来源：http://dali.jlsjyb.cn/Article/details/gtujhjnyxm.html

[A19] 交换两个变量
来源：http://dali.yangfankeji.com/Article/details/gtwnvtvemm.html

Py:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtnepvuvsw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hywenlv.cn/Article/details/gtprbdmukx.html

JS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gtmregqenn.html

TS:   [a, b] = [b, a];
来源：http://dali.iojbl.cn/Article/details/gtoqaikvty.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtljcsiiqj.html

Go:   a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtwjowaxqd.html

Ruby: a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtfasfexyo.html

C#:   (a, b) = (b, a);
来源：http://dali.kuanghao11.cn/Article/details/gtxzpqvxdb.html

[A20] 读取标准输入
来源：http://dali.tianlin.xyz/Article/details/gtkzqhgokd.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gtotegdtid.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yangfankeji.com/Article/details/gtfbwzcnbc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gogol.net.cn/Article/details/gtghituiuw.html

TS:   // Node.js：readline 模块
来源：http://dali.quarkkingdee.top/Article/details/gthriqawmb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.bjfxy.top/Article/details/gtstbzmpwh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.c1oappe.top/Article/details/gtwcrqczgi.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gtnhjycldy.html

C#:   Console.ReadLine();
来源：http://dali.gaohongyu789.top/Article/details/gtdiegpbga.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gttjestgsr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhengqikj.top/Article/details/gtxqmlgguk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtncmubzlo.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjagpdej.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtemadiwrh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gtpptyqcof.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtvzykrosq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtzgfpoiix.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnxiangtu.top/Article/details/gtbtnpifmx.html

[A22] 获取字符串长度
来源：http://dali.xylfe.cn/Article/details/gtvbrcwvzi.html

Py:   len(s)
来源：http://dali.yongpay.top/Article/details/gtkaylimhv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hfpthk.cn/Article/details/gterpbwcql.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gtpjhrutcj.html

TS:   s.length
来源：http://dali.havefunace.top/Article/details/gteqjfgaad.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gtfjqirssy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gtfxonusgv.html

Ruby: s.length
来源：http://dali.cdnleiting.top/Article/details/gtinxjhnlu.html

C#:   s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtscoxodyq.html

[A23] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtzpdatfom.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangdashe.top/Article/details/gtbvwjpdiu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gtlirjbtpx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtdpeyjbyx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtuzkqcenr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtevwctanv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangdashe.top/Article/details/gtxkzzzavp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pycfn.com/Article/details/gtzwphnvje.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgfzy.top/Article/details/gtxnkvnbry.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gtnmhhlfsw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.c1oappe.top/Article/details/gtqclzbiqw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtryjuqezr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtxralaxre.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejkzcqmb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pycfn.com/Article/details/gtgfubohhq.html

Go:   strings.TrimSpace(s)
来源：http://dali.c1oappe.top/Article/details/gtpgwmixbs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangdashe.top/Article/details/gtvddowdry.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnqzz.top/Article/details/gtciagbbch.html

[A25] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtmqndejvi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aibaodan.cn/Article/details/gtaxdacccc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzkimhocy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gtvsgyffvi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gtozglfcpb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtrwhvnmwz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tianlin.xyz/Article/details/gttnajthux.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cdnleiting.top/Article/details/gtmezxmfec.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yongpay.top/Article/details/gtrtvdtdmq.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gtuiimcjhr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.9152youxi.cn/Article/details/gtynrbqyrq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cdnleiting.top/Article/details/gtqjdpqdah.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yueranfly.top/Article/details/gtfabwpiak.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gtdegahxzz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtvefxbvne.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.haohaochexian.top/Article/details/gtaqwrfnef.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gtozbmoiwj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gtpsuaxywf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtooabppbm.html

B. 流程控制
来源：http://dali.gzhubu.top/Article/details/gtmvljodza.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtprotwhpb.html

[B01] 条件判断 if / else
来源：http://dali.iojbl.cn/Article/details/gtajrzthfh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxinkj.top/Article/details/gtotfegnos.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yongpay.top/Article/details/gtimekonlm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtprsvlgmh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtmuiombjy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtyeoyvpxt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gtyjkwfiqc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gthpolvkfv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtoeovwgvh.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gtfbtrdybq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdulfbyw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gtfuhoqdnn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtkqohcqit.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtqbypnrtt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtnbiglday.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxuanxn.top/Article/details/gtmitrtdkb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenzaomai.com/Article/details/gtmcerwnng.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gthhzayjbz.html

[B03] switch / match / case
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaqyfqxl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj202588.top/Article/details/gtkjrnfztr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtkvclcupz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtlmkjmana.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtgterskuc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqxovzmna.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.meibo888.top/Article/details/gttkxcmilk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuanzhike.top/Article/details/gthjvxgrys.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gtishhidaz.html

[B04] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtrqtzlstn.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gtwpqckirk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gthivqjhtb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtitfficeg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtqawotqbl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yvedp.cn/Article/details/gtqeelmhmq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ivvv.top/Article/details/gtkzhmqigy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gttemctmbx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tanke756.top/Article/details/gtoteihfzd.html

[B05] 遍历数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtnqgvsayj.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gtftlwlypc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtkybantso.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gtbxoirjyq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqwltcbkv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtmulmndij.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sufxvd.cn/Article/details/gtlhrpomnh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gtuzeyjokf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwjwajomq.html

[B06] 遍历字典 / 对象
来源：http://dali.kuanghao11.cn/Article/details/gtwykzpkgc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtaqwozmgc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gtppqfvncq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtahcbgvyp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwioqmpfk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gtsdbpsdmo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacmvkpho.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtevylptqu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtjntpynea.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gtetbdzjli.html

Py:   while i < 10: i += 1
来源：http://dali.mhx1999.top/Article/details/gthhzziusd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzknbkjcc.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtjicrgeia.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtnmmecydw.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtsijgvthd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtmdyzlejw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudrwhepn.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtjgawqehm.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtwyyspfig.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gtjugakvwr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtrlnljrjy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gthuxanebj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtcrpueldu.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtzmuxkgql.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gtwgqwczbo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gtzilecxum.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtvnclwkbi.html

[B09] break 与 continue
来源：http://dali.nanxinkj.top/Article/details/gtxfqxfcvx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gthfsrqnfw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtvdhiuexd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtanaohvkx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtzowsbkgo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gttnuonypy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gtrbuaoknw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gtcmntvhxk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gttgaddkow.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gtugobewmt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtzcbwwdlr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gtfnsyjunk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gtruttxpav.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtsjtaazls.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.bjfxy.top/Article/details/gtluooufxc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gtiqrfwzoo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtxdkpysja.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gtrmqyoqdn.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gtcfsprznk.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtueywaocr.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gtbsanpowb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgltbtxe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtdsswrzax.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gtclfxjxiz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtpmmpvnrc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gtiggmoxlp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gtrrdykgrn.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gtlzbimpmr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gtagacxnpe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gteqcfnfzo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtmbooyezi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtcaxrapln.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtahdnvydv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkstoaja.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtklwhsjmz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gthkszzbcz.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtmehrxmtf.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gtlrpuowkc.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gtfvqqeoaa.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtgtsrxjoi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtkpwhopap.html

Java: x instanceof Number
来源：http://dali.ehwqpu.com/Article/details/gtzzhgsixz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzguprnsc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gtpdpjdohl.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtepavixwt.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtztdsuzvm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtiacdwimz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gtjmgyqkvh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtglpjplyy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtjbwxyera.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtcmrrefjc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtsrvnqwti.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gtiqermmix.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtvsqcxmml.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtgtxgtwog.html

Py:   a and b or not c
来源：http://dali.ehwqpu.com/Article/details/gtfmwclkta.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtwktojexz.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtxdwfcvhl.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtbmywqywg.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtaryfmmyi.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtszvilrdt.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtwomozyjv.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtxkrgthdn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllittulm.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtdvvklxvs.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtqizpqevj.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtydnfcast.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtzznjpnfh.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtzgmsjhms.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtgftxxdet.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gttdgfpvfn.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtcgbmhyrq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtncyigiyh.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtevudkder.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttowfqlpd.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtzuyywjva.html

Py:   def add(a, b): return a + b
来源：http://dali.hysaishi.cn/Article/details/gtttnjqjfk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtixnthzvl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjgspmmju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdiqtrhv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtnabjhvwf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtpygqbqnf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtszbjiftr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtbstswfbw.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtskgbqzzn.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gttpmukfxg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gtmixavtid.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtsbwemdci.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gttldtpyyc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtzjjdiezy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtjqjrmaic.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gtcfrgtrjh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtreosdhwm.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtvljgrcgx.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gtglnrlzny.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljnyurdx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gteskpclha.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjilrtrz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gthyalguhg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gthikstcam.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtdcdvqaik.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtsdzxndhg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gtmyawrhup.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gtzdblyvpv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtpugqdnem.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtqsgyhbpp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtqinmxxzp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gtqvxjxsvv.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtrgelzvsy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtbhbjsuan.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtuhpqsjsr.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtxufogcpe.html


<!-- 参考信息 -->