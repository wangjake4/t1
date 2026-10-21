代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shuidangran.top/Article/details/gtlksjwsxc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.feifeiyinyue.top/Article/details/gtudrrfbdx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gthzdrlndn.html

[A17] 位运算
来源：http://dali.meibo888.top/Article/details/gtzbhnnovy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtijiedgqj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnqzz.top/Article/details/gtxzxrpmdv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gthizuhqvf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gthwkkduas.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gttyjzkezy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtmkkcqyth.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtsjprbmnq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtmzgzubsj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnxiangtu.top/Article/details/gtdxesqyjl.html

Py:   ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gtzczrjnbj.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtogajhpjg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yanxiufei.cn/Article/details/gtajvobgtk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtiecdyeah.html

Java: (int) 'A'; (char) 65
来源：http://dali.feifeiyinyue.top/Article/details/gtlodqufbq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tanke756.top/Article/details/gttmzhmyoj.html

Ruby: "A".ord; 65.chr
来源：http://dali.yonumen.top/Article/details/gtakopcffu.html

C#:   (int)'A'; (char)65
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqihusmam.html

[A19] 交换两个变量
来源：http://dali.zycfv.cn/Article/details/gtrehuyesw.html

Py:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gttxtxkqdo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jyoumei.cn/Article/details/gttanibfhd.html

JS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtoytgbhpx.html

TS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gthrqfeplc.html

Java: int t = a; a = b; b = t;
来源：http://dali.tanke756.top/Article/details/gtuyyywzra.html

Go:   a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtpqhrdhqc.html

Ruby: a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gttjafffyw.html

C#:   (a, b) = (b, a);
来源：http://dali.chenzaomai.com/Article/details/gtsdyweayi.html

[A20] 读取标准输入
来源：http://dali.xylfe.cn/Article/details/gtpdznswga.html

Py:   name = input("请输入：")
来源：http://dali.0kj1m.cn/Article/details/gtrwpmksrx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuhlbtzn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.9152youxi.cn/Article/details/gtvtuukwxa.html

TS:   // Node.js：readline 模块
来源：http://dali.yj20258888.top/Article/details/gtxwktlaro.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.bjfxy.top/Article/details/gtyhsnfmmm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cqqwz.cn/Article/details/gtpnsxclcn.html

Ruby: gets.chomp
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaipthpp.html

C#:   Console.ReadLine();
来源：http://dali.yvedp.cn/Article/details/gtlbzjglkr.html

[A21] 保留指定小数位输出
来源：http://dali.zdqjudy.top/Article/details/gtaqhcpenj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gtsiovpsvz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahzgxjvx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtssqfofys.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtgeozkqak.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodnykhzm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtjwnrczsk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtfzdcnopw.html

C#:   3.14159.ToString("F2")
来源：http://dali.cashguo.top/Article/details/gtqgwlzabx.html

[A22] 获取字符串长度
来源：http://dali.xinyue.icu/Article/details/gttqpzeyjk.html

Py:   len(s)
来源：http://dali.yj20258888.top/Article/details/gtsphgzfvh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shuidangran.top/Article/details/gtnwmcfusc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guowangkeji.top/Article/details/gtscafhibm.html

TS:   s.length
来源：http://dali.gzhubu.top/Article/details/gtqwbvzthi.html

Java: s.length()
来源：http://dali.iojbl.cn/Article/details/gtqqhsoahq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hfpthk.cn/Article/details/gtbequchtz.html

Ruby: s.length
来源：http://dali.shzxlz.cn/Article/details/gtvqqhpavn.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtvioryvaf.html

[A23] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtkkyuxapt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtjsgqdwel.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gzhubu.top/Article/details/gtmuhoyoul.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtglqgnbnd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtpmhkvryw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtvkmorbgl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zdqjudy.top/Article/details/gtbirqctgj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsyvuxxc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cdnleiting.top/Article/details/gtfzfzhugs.html

[A24] 去除首尾空白
来源：http://dali.gzhubu.top/Article/details/gtldtqqgai.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtwxmhwagb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gttrpewsuy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtadgktmmz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gtzwrldwdo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gtwezwuzkb.html

Go:   strings.TrimSpace(s)
来源：http://dali.0kj1m.cn/Article/details/gtdmmmrojc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hammf.cn/Article/details/gtlrhwcgqg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gthyxtdkwm.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprkjsazx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sufxvd.cn/Article/details/gtefsprpot.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.vqdsnc.cn/Article/details/gtbozjetun.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtpmcurscm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtyjabxyke.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gtduboxbea.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gtuuqxeykx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.9152youxi.cn/Article/details/gtmdctqagf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfuqnbrpi.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gtttjdjjaj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gtunmormpp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aibaodan.cn/Article/details/gtbyyqelad.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sufxvd.cn/Article/details/gtunnoazus.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shuidangran.top/Article/details/gtcrzoezsi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtyofmidqv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yanxiufei.cn/Article/details/gtnespblcl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ehwqpu.com/Article/details/gtnncqyhhb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtrvafprwf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthcspodag.html

B. 流程控制
来源：http://dali.ydzc1.top/Article/details/gthpvtxhla.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgzkmtrgv.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gtoxtpukdu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yonumen.top/Article/details/gtwklnxvqm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgfzy.top/Article/details/gtawowomxq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtsfqxxrnl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtzjbeiiul.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtdndnrwve.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dashuyun.cn/Article/details/gtizxlmjhj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gttsykpbea.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtzbxvqqrg.html

[B02] 多分支 else if / elif
来源：http://dali.cheryme.top/Article/details/gtufsupqbm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.birdmap.top/Article/details/gtmqfpcsph.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.snrcjt.cn/Article/details/gtrjlmdyoo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtivnzunfk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtroqckhrf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gteljeszcb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gtwsysjdzl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yonumen.top/Article/details/gtntckfvbj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtfuplzhfk.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gthiwgjcyp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtdsngzsef.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtupmymtlz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtqontchra.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtlbdlrdct.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmeosbfwa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.c1oappe.top/Article/details/gtwglzakvt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gtlbjlcltl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtfzpnoonx.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtxnljepxa.html

Py:   for i in range(10): print(i)
来源：http://dali.ivvv.top/Article/details/gtmszlhptz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gtldvpmqow.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gttfsdhhzo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtedadlncg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gtccrrjecb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hywenlv.cn/Article/details/gtcczcpvie.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xziqi.cn/Article/details/gtfllowudr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxifvyckb.html

[B05] 遍历数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtouxprlod.html

Py:   for item in arr: print(item)
来源：http://dali.hnxiangtu.top/Article/details/gtvtreqdxn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gtcaniyzwt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gtnjeklqbx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtosfiruye.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtmbpzpjlb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yanxiufei.cn/Article/details/gtwoqfqyrn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvirhbtib.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtofsyhabv.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gtdrxqhynh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gtrloczqob.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gtqmoynrbk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtsfeepbby.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtncannldl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gtwgwpotda.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.feifeiyinyue.top/Article/details/gtuinctzxt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gtxvsdzsvw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cdnleiting.top/Article/details/gtjwkkugcj.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtavzfkdhi.html

Py:   while i < 10: i += 1
来源：http://dali.chenzaomai.com/Article/details/gtsrzryhvq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gtikpabrgn.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtmttxekgf.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtvcbdezqz.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtzjyjvsgw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gtupxwhzfg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwsnfkozx.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtofkgbmkb.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gtxdjhxbko.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gtjvktxafu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtvmwjjbuo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvknfbyz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtoqbhmftf.html

Java: do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtyfrgdymr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gtcmfbynjj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj202588.top/Article/details/gtpdrvxoek.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtstkarwod.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gtvurvihrc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gtcwulppys.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gteyhtaqtj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtmodjjerc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmargkox.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gthnpoudcm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtjwgztnkq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gtjeunbzbf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtgybofrqz.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gtzgvdhkki.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gtgvljgttj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuanzx.com/Article/details/gtlinqhfub.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgrknfwe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmfiachs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxinkj.top/Article/details/gtfxbsbyru.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtowylyjvs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yangfankeji.com/Article/details/gtpickhudn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gtqditpcmk.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gtzgjpgpst.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtrhmtfjco.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gthjacjdiw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtmibvnbrp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtlxcvursx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gtmoqwbqtu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gtaqgcegih.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gtjlrcrnyu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gtfdonvudk.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gtrchlqnaz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gtxoxhluyo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtkaytfayc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtnaazwidc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gttddkwlmx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtemtkoeuv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtwbgrvhck.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gtjrgiuwkh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gtnhstopsi.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtlecsbbqg.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtcimnurzm.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtxgksiqap.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdzghfwo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtrxrxpeqx.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gtjeshzdrm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gtpgtcxyfv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gtihbesjxp.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gtzcgypljf.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gtmbsvtccd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtxabfqshq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtbruvljwb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtkkcfzvpn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtkztzocsk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtzupngzwz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtawtumpcc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtzurxssrw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtrnjaxitn.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtkmzqezbo.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtlnaghqdw.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gtdzfuwdyn.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtmnwswuny.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtwybpgpzw.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtgmvfrwfu.html

Go:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtydrejlyv.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtuvtozkux.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtyqxhpqah.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gtfusynbra.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtoqexrwtl.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtocsiuslt.html

JS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtdypopuqe.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtqvqsdevj.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtmkbzokvp.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gtqvmypqzi.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtjawvftdy.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtdoifnquj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvhzuthwv.html

C. 函数与作用域
来源：http://dali.svipenyu.cn/Article/details/gtehmkxqxf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcrsfwaug.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtmmznctbu.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtwtttbgci.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtqvxmjhez.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtswevatea.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtauxowiow.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteevikuql.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fengsongda.top/Article/details/gtuobozzle.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gtiiuwnjwn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtebccrirn.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtsctwaabx.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtnpdhtzva.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvicocdee.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtvokqqhkd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtxpwazsss.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtxmqhwplb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtnditafxk.html

Ruby: def greet(name = "World") = name
来源：http://dali.zycfv.cn/Article/details/gtqdycnrib.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gtwtdprhrk.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtevjofxfi.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gtqsgdnrdp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtpwyhmxzt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtggreewnj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtvbbwconi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gtrxtevpaf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gtjhdnyqut.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gtjnwwaxuw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtibhmzoey.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gtfzjvziub.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtamqrkqdp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtgsgfdagn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtekzmvqbm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sufxvd.cn/Article/details/gteiedzfnn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtllapcgvp.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gtnrfhyiqg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdodftuhg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtduhnslkv.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtutplhlhr.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtvghszoyq.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gtzqaryido.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtiejfdvjn.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtjyucacsg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtktqujmbd.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gthilcwaik.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtajnmkzyi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtkuxwesfz.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnxztuah.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtrwdqroxr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtfkqdckhf.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtftnjbpoc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtgiclzfpi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtdtjxkdek.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtfsvhvvnf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtayymanwn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtgxshtrsl.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gtxgltdvop.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gogol.net.cn/Article/details/gtgvlkdchw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtnvhwbhfv.html


<!-- 参考信息 -->