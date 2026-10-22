代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.jqgfzy.top/Article/details/gtrkvaqwrh.html

C#:   var value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtntvhmaxq.html

[A16] 真假值判断规则
来源：http://dali.hysaishi.cn/Article/details/gtopfvfjjr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xinyue.icu/Article/details/gtgxijavte.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.fengsongda.top/Article/details/gtmxkamxbj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daria6918.cn/Article/details/gtjacqwnjd.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gtzrajzskk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.0kj1m.cn/Article/details/gtdcqlgttz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gtpzvrimle.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmikdjcb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gtnrbftfuo.html

[A17] 位运算
来源：http://dali.yj20258.top/Article/details/gtvainrqoi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gttwavwgiy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shuidangran.top/Article/details/gtfpugqxsw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtclghyebb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtlxvegdxq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtvabtghnd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtxbgwweyr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gterdhwxcw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlqblbux.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zycfv.cn/Article/details/gtiparfdwu.html

Py:   ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gtjmxpgpbr.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuanzhike.top/Article/details/gtsbimyjvp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gtmmcbuepe.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgfzy.top/Article/details/gteyavsgzv.html

Java: (int) 'A'; (char) 65
来源：http://dali.aizwys.cn/Article/details/gtcrrmzawj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gttlszakbr.html

Ruby: "A".ord; 65.chr
来源：http://dali.shuidangran.top/Article/details/gthazhvdxl.html

C#:   (int)'A'; (char)65
来源：http://dali.pycfn.com/Article/details/gtuzycuyjj.html

[A19] 交换两个变量
来源：http://dali.yuanzhike.top/Article/details/gtxykvdgpc.html

Py:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtmytfyuwb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xylfe.cn/Article/details/gtcnxumwtt.html

JS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtpdwfsgwo.html

TS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gtenlagued.html

Java: int t = a; a = b; b = t;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmojwbcjp.html

Go:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtdwgccqcv.html

Ruby: a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtfslfptdb.html

C#:   (a, b) = (b, a);
来源：http://dali.jianghu66.top/Article/details/gtacwnrdmj.html

[A20] 读取标准输入
来源：http://dali.yonumen.top/Article/details/gtkapifqfj.html

Py:   name = input("请输入：")
来源：http://dali.dashuyun.cn/Article/details/gtwoclgxva.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xuanzx.com/Article/details/gtnwnivvyx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcznuoma.html

TS:   // Node.js：readline 模块
来源：http://dali.sysykeji.top/Article/details/gtujdkehpc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ppjwa.cn/Article/details/gtnnnkhlqu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tanke756.top/Article/details/gtrdybpcuw.html

Ruby: gets.chomp
来源：http://dali.c1oappe.top/Article/details/gthsjbjowg.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gtiuisdxhi.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gttaftovum.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gaohongyu789.top/Article/details/gtsesfncxu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtpwiauyfy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtdzonyelv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gtguftqgkx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtkdlxkxpe.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gttkrzlbem.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtgompwabp.html

C#:   3.14159.ToString("F2")
来源：http://dali.yonumen.top/Article/details/gtcdkqkwyv.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gtqplxleyt.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gtyrydcjun.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuetiantiany.cn/Article/details/gtywaajgkb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenzaomai.com/Article/details/gttozxwecn.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gtqhuuglil.html

Java: s.length()
来源：http://dali.chenlongwang.top/Article/details/gtbyflscpc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sysykeji.top/Article/details/gtnsladfjn.html

Ruby: s.length
来源：http://dali.mhx1999.top/Article/details/gttimodmtn.html

C#:   s.Length
来源：http://dali.xziqi.cn/Article/details/gtddqcvsvl.html

[A23] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtgvwhgfpo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtgoowzmth.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.0kj1m.cn/Article/details/gtoriibrsk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtivcweofl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtjyswffxb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtubkgpwpf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gtioqpxmhq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfnjnswq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtehcsbxtx.html

[A24] 去除首尾空白
来源：http://dali.jlsjyb.cn/Article/details/gtwhrrworg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtnoixhkxc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gtpzulmtwp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtbusynook.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtxwhikfgf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gtpcczfati.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttqcorbxs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gtfqzaodwl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtppenfbuv.html

[A25] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtffvmicnp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gtawkeguod.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtkrdskedb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtwrljajrc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtdsdfzjzs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daria6918.cn/Article/details/gthwnqcpei.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtbzstiqft.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hammf.cn/Article/details/gtvjqkmaxq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gthazjwzdc.html

[A26] 类型转换总览
来源：http://dali.yj20258888.top/Article/details/gtxeskoiva.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gtwzvvtwua.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gtnbkhwfhj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gttdylsoic.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhoulong.xyz/Article/details/gtrknvjkcr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtuobqacmj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hysaishi.cn/Article/details/gtaxnfmyqf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gtblxwrvng.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtxodrnhek.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbsemydmk.html

B. 流程控制
来源：http://dali.mhx1999.top/Article/details/gtkanusopz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxmpbxsne.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gtmnkvjnhd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtghauiwga.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrzwgpqel.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtbyqmoszj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtndhbiwvm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtvkbjbyxj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gtiuskwpqw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258888.top/Article/details/gtjdjzeakd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtitdpclka.html

[B02] 多分支 else if / elif
来源：http://dali.pycfn.com/Article/details/gtyqyjzqrf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gtsczbdrms.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ppjwa.cn/Article/details/gtfdpkczmr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtcvdqpemh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gttbrnhilo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtadfbkqsj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgufenzy.top/Article/details/gtzjcicgsj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigufen.top/Article/details/gtfmbankfm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtxxreutbh.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gttcelhymn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yueranfly.top/Article/details/gtgcvsopmr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gthlrqfbpf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtdqifnugm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtihzikljv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtrlkzetme.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtavzshogp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xziqi.cn/Article/details/gtgiyeilrp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtqrwsscdi.html

[B04] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtvjqnkftj.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtlkbqwhoe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gtofszseyt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdwxxpsqd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtzdxvudyc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gtoqxecfov.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgufenzy.top/Article/details/gtedbuokte.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fzhhl.top/Article/details/gthghavaou.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtnoedtyso.html

[B05] 遍历数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtocoyjicy.html

Py:   for item in arr: print(item)
来源：http://dali.mhx1999.top/Article/details/gtvtfcencz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.quarkkingdee.top/Article/details/gtmysqzwdt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtbhkocamx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gttfumnxdh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gotoacloud.top/Article/details/gtjfmuidlv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258888.top/Article/details/gthukkmibm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gthfxzsmkj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtzncstafr.html

[B06] 遍历字典 / 对象
来源：http://dali.kuanghao11.cn/Article/details/gtpbozlekr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pengpengdd.cyou/Article/details/gtnfzsooll.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gttydiyokb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbnqmktok.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gttaeiqcur.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gtzwoiczdy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtvfttdfje.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gtsjstjkxg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gtawpguiec.html

[B07] while 循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxwijelo.html

Py:   while i < 10: i += 1
来源：http://dali.haohaochexian.top/Article/details/gtlvzgeyfl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtsmrdtdar.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtnqkizypk.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgofpxjva.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtuwwtmpym.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gtxwckrdfl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.316326.xyz/Article/details/gtqgcbtjac.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtrakuvyvj.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gtdmbtayqi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenzaomai.com/Article/details/gtugpzeqyf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtuuqmnffc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtoojbsbrs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtrmvcjpfc.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtecyysosf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtqkkpagix.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gtanoqjsyp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gthxgogpkr.html

[B09] break 与 continue
来源：http://dali.ppjwa.cn/Article/details/gtouvvfdze.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hywenlv.cn/Article/details/gtfucfwxdj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtqlaxdcjj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtdmxxcaxr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtezaljmgk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtqgrxkqeg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gthilojbvj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtkbhfinzg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gttsjgmgom.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtgwnknqzk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gtsoqayfia.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gtiptdmhqe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtufnkocbh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gteehccphu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gtoyeojiey.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtngxilvso.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sysykeji.top/Article/details/gtmommdgvp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gtmwamkmjy.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnktgaqks.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gtzjkklxlo.html

PHP:  range(0, 10, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtdhwuwskr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtalustqvs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtfqpecygf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gtwlasozph.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gtbuciclct.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtugqlwkhu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gtzyrcjeux.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gtfekqxykd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gotoacloud.top/Article/details/gthsdbqnsw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gtekqdpxbc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtieyciidw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtnsujspus.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtuxiblyoy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gtgghknvsa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenjidiqi.icu/Article/details/gtqrmdqpsh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtutbyekid.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtyddwdhwy.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtccoamrrn.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtxjinxsey.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gthdstutcr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtiyuuxldk.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtzluosnqw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gtaaamyrdc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtqlqtdjlv.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gthqazgnxl.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258.top/Article/details/gtzbaxxwhz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gteimrjdkw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gtrasiplvj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtbiyutwmo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtkazqxekh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcckfmbm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtkzbasbtl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gtakjciefc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtaowmepbq.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtcfmgniiu.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtrcdmjtyt.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtelppupju.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtzsmdflvp.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtkanvkueu.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gthlafdetn.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtebgjqblf.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtlbvbrcpw.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtifrsrswj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvnoxrvp.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtckeyzaxb.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gttxisnrhf.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtcdvkmbca.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtvyowbdic.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtyupmszsg.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gttlffnnml.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gtvitpoxrc.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtqnpvxbxx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxrhpuclv.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmdazzmv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrypgnmgw.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtjghpcxsh.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtjkvkifoe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtttoiyqzk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtfaflzkqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtwfhfbuyz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtpelfyuhb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtozwmxmzs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gtxxookzzp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtsshgpmge.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtfnmgohcm.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtdalhsenb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtuewoirdc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtakjsdxah.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtfssctyzt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtolgppxef.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtndxieskk.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtpoqhivni.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tanke756.top/Article/details/gttccpnloo.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gtkonsxpkn.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtsnvpcdgp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jianghu66.top/Article/details/gtheirghdf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtilwglaxm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtjcvpxlso.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtllplmlwx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtrstrbgwx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtwfcvatgp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gtmqviazzd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhlbqqle.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtbwgfprng.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtaarwknwf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtaymkcxsp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gttxmypren.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gthsutldmn.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gtmeanihve.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtscyffnqj.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtbebggrfo.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gtxawgacgx.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtdrrglfww.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtsqgwvenc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtnpyewgxz.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtfttxezim.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmozqjdk.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gttgqdefsl.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfbskorl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gteymmrgwr.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtbijwwtoc.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaisfltxx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvefptsf.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtouwfhvad.html


<!-- 参考信息 -->