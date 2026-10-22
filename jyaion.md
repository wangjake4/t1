代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.guannengcc.top/Article/details/gtjulntbbu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtxjckgyju.html

TS:   if (!x) {}
来源：http://dali.wangdashe.top/Article/details/gthoifqrab.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jiagoushi.top/Article/details/gtkfqaeknx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gtzmqckkeq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zdqjudy.top/Article/details/gtoylkcrso.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtmfvjtmpo.html

[A17] 位运算
来源：http://dali.snrcjt.cn/Article/details/gtkzjeystv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtgojzgwdw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ydzc1.top/Article/details/gtywhfeyne.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtdcdibarg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtvleswoix.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtwbzksriq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxwbveqg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtjtykbvbk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtqkiwsnxb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxinkj.top/Article/details/gtszsytcoh.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtzjnpmiqw.html

PHP:  ord("A"); chr(65)
来源：http://dali.xylfe.cn/Article/details/gtraartrgh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.mhx1999.top/Article/details/gtouwkenuj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gtyciislvs.html

Java: (int) 'A'; (char) 65
来源：http://dali.shzxlz.cn/Article/details/gtktuzwrbd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlmayqhc.html

Ruby: "A".ord; 65.chr
来源：http://dali.ybcxt.top/Article/details/gtidbttivv.html

C#:   (int)'A'; (char)65
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkocgxvtt.html

[A19] 交换两个变量
来源：http://dali.guannengcc.top/Article/details/gtoqvzcwhu.html

Py:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtowqmdwrl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yvedp.cn/Article/details/gtzxfpvwqb.html

JS:   [a, b] = [b, a];
来源：http://dali.bjfxy.top/Article/details/gtiejozbse.html

TS:   [a, b] = [b, a];
来源：http://dali.nwbrower.top/Article/details/gttfkhefyi.html

Java: int t = a; a = b; b = t;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabdgzmoj.html

Go:   a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gtwbaqckhv.html

Ruby: a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gtgykxwpzg.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gtyhczsjri.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gtxyjqlzhs.html

Py:   name = input("请输入：")
来源：http://dali.zhongyouzk.top/Article/details/gtojbdauxd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.svipenyu.cn/Article/details/gtapmxozwx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ppjwa.cn/Article/details/gtuxyjhols.html

TS:   // Node.js：readline 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtnlfaphps.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yanxiufei.cn/Article/details/gtdcbegcgl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.316326.xyz/Article/details/gtmjxkpzpb.html

Ruby: gets.chomp
来源：http://dali.zhongyouzk.top/Article/details/gtykoqzwsd.html

C#:   Console.ReadLine();
来源：http://dali.chenjidiqi.icu/Article/details/gtdefkvpql.html

[A21] 保留指定小数位输出
来源：http://dali.bjfxy.top/Article/details/gtzbdhkrja.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtgtrnyteu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaxqdcux.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtagslehhq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgstlykgi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtdcjnjxka.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtwwrppyef.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtvjemdxzk.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhiwuduotai.top/Article/details/gtlpnseuuo.html

[A22] 获取字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtxiefsekb.html

Py:   len(s)
来源：http://dali.cashguo.top/Article/details/gtalidooun.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sysykeji.top/Article/details/gtmkfppbic.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhixingplan.top/Article/details/gtnuuwpuch.html

TS:   s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtzlesrrqc.html

Java: s.length()
来源：http://dali.yuxming.cn/Article/details/gtwmxhnzqm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtvtbqdxvd.html

Ruby: s.length
来源：http://dali.haohaochexian.top/Article/details/gtmjtfnpko.html

C#:   s.Length
来源：http://dali.jinqigufen.top/Article/details/gtuwyxxcaj.html

[A23] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtbsjdwwoh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.aizwys.cn/Article/details/gtypnqyahf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuanzx.com/Article/details/gtjslidxhd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtffzjsbua.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gtzhmhagtm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtbnvrxrut.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gtwkcaalbx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtrqmoggml.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkslhwwv.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtsmybjaby.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.9152youxi.cn/Article/details/gtkumgaymy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuefzpatc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtjvvtzdkh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdwdwlge.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.birdmap.top/Article/details/gtmcfbiala.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtzxlkrtbe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shuidangran.top/Article/details/gttpnirfzd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gtbrbmxlrx.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtczjjmmss.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gtzevhohpe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gtsdfvfdgg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gtacrwzhzu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtscrvavpq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yangfankeji.com/Article/details/gtyiqvmxzi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gtaqhyftuq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gtjbbflxmo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtuqzdzccf.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gtnycdqcwh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtjzlgaxwg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gtoyrecndz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtlfywufau.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinqigufen.top/Article/details/gtrgjodbwd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtsjgfghso.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.bjfxy.top/Article/details/gtzuctqgal.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.haohaochexian.top/Article/details/gtoqfcazku.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtfsyeyqon.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsfqgvbdi.html

B. 流程控制
来源：http://dali.sysykeji.top/Article/details/gtgyrxhpna.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuakqrwtw.html

[B01] 条件判断 if / else
来源：http://dali.yuanzhike.top/Article/details/gtiakybaha.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtzqpfkbuh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fzhhl.top/Article/details/gtsvowujgb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtaywhhxsa.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdylxptn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtagwfmcdp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gtuzagclrq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtioqdbtiy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtesswxele.html

[B02] 多分支 else if / elif
来源：http://dali.havefunace.top/Article/details/gtimoukhgb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gtnmpdpkwp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gtvnhziptp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtpuhhtsuz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtsoksiqcu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtrrpfgyuf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.iojbl.cn/Article/details/gtvbagbach.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgufenzy.top/Article/details/gtnqsefewz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtfkwngvfw.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gtaggpguna.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgfzy.top/Article/details/gtzkpxhlxs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtquwdzjwp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtndoxargc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtlsppwghs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtchgnslze.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlytrxuex.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shuidangran.top/Article/details/gtytclrkks.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtbmsztkln.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtnkvszjnr.html

Py:   for i in range(10): print(i)
来源：http://dali.hywenlv.cn/Article/details/gtrunqqvjo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.mhx1999.top/Article/details/gthdlijvvj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtbkxadrwt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtvjweqpqw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gttyuegqff.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gtzbkoumyz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gtholycjfi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.iojbl.cn/Article/details/gtqpnyqohl.html

[B05] 遍历数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtsanwkxho.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gtfxqzvdyz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gtkiwueyoh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlnzsdxkh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gtndyinnyw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cdnleiting.top/Article/details/gtauaqlchm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cashguo.top/Article/details/gtqwjeiuef.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yanxiufei.cn/Article/details/gtlmwpixfq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlbdmfqau.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gtykmouash.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxuanxn.top/Article/details/gtlndpqdxb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtcqybwhms.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.kuanghao11.cn/Article/details/gtyljvlobi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowwphoxx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwggofrt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gtjxvjolfg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gtklwtecao.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzvxqpnd.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gtjxgkfqno.html

Py:   while i < 10: i += 1
来源：http://dali.zhengqikj.top/Article/details/gtgcnbrzpi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtqhoundjv.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtzytjjfcs.html

TS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtwztqtlux.html

Java: while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtebwqhuei.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gtncqokpww.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtfdjhwukf.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtksnoxdll.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gtoybpaoie.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gtkefqcied.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtuxiobpwg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtzzrszgcz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtdckgfjmd.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtgpfjjmek.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gtqsnqffwe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gtiigfrxye.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtxcpqavom.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtmswzpvik.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtpiushhvc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gttzixjcky.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtxwjwahgo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtjjfznzwo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gthemwjirf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gtjrfiehix.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gtsmlhndcu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtrpebqgnt.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkvwftdi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gttbnukobg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gtmalusdct.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtcbpgqoqm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtfcckdpnf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gtmoceagob.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gtuxncyttw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.snrcjt.cn/Article/details/gtgxygwsxd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtmmsmgyoq.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtpmxjrwtm.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdojxwprj.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gtlyqbfqxf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtlkywvnbf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtfgcphovt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtngidtdoe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtyfecwixx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gtcmhkrlap.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gtpdvmjxxr.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtahaujdsi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gtazijlpgi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtbftiaufn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtuhscptiv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtutcxbndl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtenzftotb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfzjqtncr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gtxlbqnzvi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gtpddbkddb.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtfzrybsjb.html

Py:   isinstance(x, (int, float))
来源：http://dali.ybcxt.top/Article/details/gtbypttffk.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gtxrbibmfl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtohwdsjcz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtpxigsgcy.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gtnvrdyoha.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gtrtonawey.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkvyuzkf.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtlctkdsdb.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtgabytcwk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtmxejnrii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gtrhckrkep.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtubrmctjo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtoaajfzts.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtaiebboqv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtcxkjgcpb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtlmkqrcuz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtnqmvgajn.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gtaorgslxb.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gtbhzuzqbs.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gtnrkkwqlr.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtjhnuzmws.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtpdxsdoev.html

Java: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtnqpxylvm.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtleythtdr.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtptkegctq.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtagzpsxsk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtclciwfjr.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtevmobwbk.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtrpdwklbb.html

JS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtyokmewft.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtmbwvpaoh.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtakcicvrv.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gtpouyndfw.html

Ruby: return if data.nil?
来源：http://dali.yvedp.cn/Article/details/gtiplfjwgc.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuojpagar.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqrrdxuup.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gttazvtzft.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgplvsumr.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtczkmsjaw.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gttvyajdhh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtjgdevlto.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtgsctwlne.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtlnlygqkb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtwxtosfrz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtpvrstrpi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtibudbzmp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtpcwechvg.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtattxujcc.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtthquslny.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtpngxxify.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvrtvamiw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtjlrjajml.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gtqdnkidjk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtzaguonvb.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtyqsaewly.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtjjynbvwx.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtuotrfmao.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhknluio.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtmyohirsq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtbzgsfhlf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtkefuzvwd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtjdefhrwp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtddqgliqn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gtkpdhbdgi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gtpfcrpqdd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtcoyeobbw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtshfoovdx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtjkwhhfzp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtdbzrtysq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gtdnsvvrpn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtdgjwvkzm.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gtvlbqxvfa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtgdolezms.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtcyblaesf.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtfmrdunhk.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtcyymqhut.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtzkvuvjfm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtuvcyzhdd.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtxvcvplsj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtjdawpxho.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtywlpfhjj.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtwhkeztep.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtpmdbeacd.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gthecfpkbt.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gtjwtbwywc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gtyhvupqjy.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtofzfvdib.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtlbwxwmbr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtaqcuwdvq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gtxnwuqbhl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gthsudxout.html


<!-- 参考信息 -->