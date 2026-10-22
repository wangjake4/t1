代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gtenffjvqk.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtghclhhph.html

[A16] 真假值判断规则
来源：http://dali.gotoacloud.top/Article/details/gtadjyqfnj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gtpkyykviz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.guowangkeji.top/Article/details/gthiikyzxg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhengqikj.top/Article/details/gtcjhwrxhw.html

TS:   if (!x) {}
来源：http://dali.xinyue.icu/Article/details/gtxabzzdot.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gtyfvahjwm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhixingplan.top/Article/details/gtgvymynfu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cashguo.top/Article/details/gtuuvfokvu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cashguo.top/Article/details/gtcvixmqkc.html

[A17] 位运算
来源：http://dali.jinqigfzy.top/Article/details/gtgtyuvhwx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtkugeuwrc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.redwolf501.top/Article/details/gtheqghyke.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtgxokibgk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtscvaugzm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtszjaodpn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gthvsxzxvr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtcuvgetls.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtmieegfnq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.pengpengdd.cyou/Article/details/gtkqfjcqow.html

Py:   ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gtxzflwqrg.html

PHP:  ord("A"); chr(65)
来源：http://dali.yueranfly.top/Article/details/gtucjclnwz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gthuqceuwb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtdnltpgxy.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenzaomai.com/Article/details/gtruhklgyw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hysaishi.cn/Article/details/gtqjuympmh.html

Ruby: "A".ord; 65.chr
来源：http://dali.fengsongda.top/Article/details/gtekjzwqlv.html

C#:   (int)'A'; (char)65
来源：http://dali.gzhubu.top/Article/details/gtpfhqqwtp.html

[A19] 交换两个变量
来源：http://dali.daxiang520.top/Article/details/gtsxcoaemx.html

Py:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtxkaqrfyq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhoulong.xyz/Article/details/gtvpnkmzrh.html

JS:   [a, b] = [b, a];
来源：http://dali.pengpengdd.cyou/Article/details/gtjeiquchs.html

TS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gtxxsdfskk.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj202588.top/Article/details/gtaafhzaff.html

Go:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtrqqzzvex.html

Ruby: a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gtkjhkvcoj.html

C#:   (a, b) = (b, a);
来源：http://dali.redwolf501.top/Article/details/gtwzkdrnjp.html

[A20] 读取标准输入
来源：http://dali.shuidangran.top/Article/details/gttpfgronq.html

Py:   name = input("请输入：")
来源：http://dali.chenjidiqi.icu/Article/details/gtdxiydjcm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pengpengdd.cyou/Article/details/gtfmeeqohm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gotoacloud.top/Article/details/gtnjxxhtao.html

TS:   // Node.js：readline 模块
来源：http://dali.yongpay.top/Article/details/gtrusfosuy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhoulong.xyz/Article/details/gtghyfrxcq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenzaomai.com/Article/details/gtvohjvlsi.html

Ruby: gets.chomp
来源：http://dali.daria6918.cn/Article/details/gtijbdxbxs.html

C#:   Console.ReadLine();
来源：http://dali.jlsjyb.cn/Article/details/gtkufjvphb.html

[A21] 保留指定小数位输出
来源：http://dali.yj202588.top/Article/details/gtvxdmvqih.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtjgiynymk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtjmrriean.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtdbrwuifn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtczdhugvg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtehoirapi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gthrsfslyn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtgawmdsgy.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gteavpczjf.html

[A22] 获取字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtpngwjbqa.html

Py:   len(s)
来源：http://dali.gotoacloud.top/Article/details/gthpsdtxxd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daria6918.cn/Article/details/gtvzrykdel.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.birdmap.top/Article/details/gtqbfdzfce.html

TS:   s.length
来源：http://dali.snrcjt.cn/Article/details/gtiewijoim.html

Java: s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgaemkfn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenzaomai.com/Article/details/gtztmkewco.html

Ruby: s.length
来源：http://dali.andypj.xyz/Article/details/gtqorcslcw.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gtgnqzdgur.html

[A23] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtefqqpied.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yongpay.top/Article/details/gtxuxxnuib.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.tanke756.top/Article/details/gtqsnlkpmg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtalbtoinx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtdticpxnp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gttozxxtrb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnxiangtu.top/Article/details/gtgllpciob.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtsdmkhbzj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgfzy.top/Article/details/gtjrzojwls.html

[A24] 去除首尾空白
来源：http://dali.feifeiyinyue.top/Article/details/gtumkjnkvs.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aizwys.cn/Article/details/gtalqyiprz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuxming.cn/Article/details/gtjcdouqwt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gtbvehuhab.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxmxzjmg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cheryme.top/Article/details/gtzpvpcjqe.html

Go:   strings.TrimSpace(s)
来源：http://dali.ppjwa.cn/Article/details/gtxpcfbckk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yangfankeji.com/Article/details/gtohcbrgpq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj202588.top/Article/details/gtvolohhjf.html

[A25] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtsbsrjamz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gtdgynhllr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cdnleiting.top/Article/details/gtfxfgoshm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtdcalqkcf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtkfjyqkrw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gtszlodbpy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gtdyhkmmds.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shzxlz.cn/Article/details/gtkuhwighy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.9152youxi.cn/Article/details/gtafzwzxqn.html

[A26] 类型转换总览
来源：http://dali.gotoacloud.top/Article/details/gtidehdlan.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hammf.cn/Article/details/gteftjgwqk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258888.top/Article/details/gtrpofvati.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hysaishi.cn/Article/details/gtbvkunqda.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gtozdohigq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gtfkygtzfl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gtopvdytfc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtmyrxuocl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtnydxumrv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtileuxwnu.html

B. 流程控制
来源：http://dali.andypj.xyz/Article/details/gtlpknmqka.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttjzzkbtr.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gtbwfwkagl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gthyyqzuob.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gtgmfktrde.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtusqtdbvv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtjghdrgmr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtqxemmdis.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gtspmzlvif.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gtyqjposcu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtvxaattom.html

[B02] 多分支 else if / elif
来源：http://dali.fengsongda.top/Article/details/gthzmwvzen.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwieqnssb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.9152youxi.cn/Article/details/gtndluoxde.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtdsesblho.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtwirdauyo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtteggonhr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daria6918.cn/Article/details/gteeecijpz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gtnewlnbor.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtivmnlflv.html

[B03] switch / match / case
来源：http://dali.fengsongda.top/Article/details/gtkrgrhixx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gtaqydnhch.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtjhsemocv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkttrdyej.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtlbyjydks.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtysyopyyo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtoajtcthw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangshuangyany.cn/Article/details/gtnkwgyriu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtilqpzxzp.html

[B04] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtijkxwsal.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gtabdiyhor.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gtotppivmf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gtogsatiyv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtcamloglv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtlebkqixy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhongyouzk.top/Article/details/gtvrjffvox.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258888.top/Article/details/gtplglulxg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cdnleiting.top/Article/details/gtauqstfge.html

[B05] 遍历数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtrtwbgtkj.html

Py:   for item in arr: print(item)
来源：http://dali.sweek.top/Article/details/gtiganiqir.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ivvv.top/Article/details/gtomgwpkxe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtaeltehed.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtvzvwhasi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pycfn.com/Article/details/gtayorzhdw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gtdxjmvvqs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gtazlfmfel.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gtxwreorxx.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gtbkfgajbw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gtcuurxhch.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gtknyogdgn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtmuhdjlqs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlyldmkuy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.andypj.xyz/Article/details/gtyhezuczs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtzkaktztw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangdashe.top/Article/details/gttnvbjkty.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtusclokni.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gtntkgmlzc.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gtwioigwsw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlrldoyq.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtppjrqhuf.html

TS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtjfxawyrl.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtxftlznnh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.redwolf501.top/Article/details/gtjlfaapsg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aibaodan.cn/Article/details/gtkxqlhpep.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtixtieztl.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gtrplccejk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtravhmqrz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtzwxrxajw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtpkaiftap.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtkmmwnpbg.html

Java: do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtdeaclmfc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmxuiulo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gtgsiwespc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtiovctanz.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gtbooczlgx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gtcrgagloa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtnjcrarkl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtngidvlma.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gteajweepq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtramkwuvm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtbvadzlsg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtiwzjfojb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtcyfkblig.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gtjefzavas.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gthxfwcmex.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwhwroswi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gttwkbdumu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtnybawldf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtusoppkri.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtvvdntryy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj202588.top/Article/details/gtkhwmoqsk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gtvldlqxqq.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtgatwllmk.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtxuwmjhhp.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtygowthad.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtcivhpldw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtjpkxdbut.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gtpdauwfrv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtwkxtjjmr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gtwtrfxghq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gtyhpbmofg.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gtqbuxghwc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuxming.cn/Article/details/gtzzgurcmq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gtfbnpayql.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtmhksksha.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtuwmsxejk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtgpjttepp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gtgudieagn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtcvzcyljv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkouzvks.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gttadjsmgm.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtgndhadda.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gtrtsjrifo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtzgivvtcz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtcwifnyza.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtpbghnuvx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gtzxhrxfpu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gtgyibnkht.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gtbehvkhds.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtnlkvlqnq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtlthgdqye.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gtqipzrzub.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjmlnydp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtowwharox.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpntkolso.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtrklfdbag.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtjoxymtpa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtdxdxemgb.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gthfjeowjl.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtpplcnnei.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gtmmvekmkt.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtpmhglrwd.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtrfvcsbnx.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtkfalnsfy.html

Go:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtfzfkbvhw.html

Ruby: a && b || !c
来源：http://dali.sweek.top/Article/details/gtrexpoqpk.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtnvfkoxwy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtncvymsjc.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gtilxizxas.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtekolugxs.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtpowgxuoo.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtvgvhmtes.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxlrpbcf.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtcycdlidm.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gtmqmnkxjh.html

C#:   if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtjldlnlag.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgttxkmmp.html

C. 函数与作用域
来源：http://dali.svipenyu.cn/Article/details/gtkeizatma.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtquqmepsd.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtnlbjlaev.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajdthwuw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtpwfnzidu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtihpxazwk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtweytdntr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtmwrqrlyw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtumxhmplu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtuuvhmwml.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtpgtgdmhz.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtfvnfalfe.html

Py:   def greet(name="World"): return name
来源：http://dali.zhongyouzk.top/Article/details/gtvvrokrjl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gttzhyljxa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtngewezgu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthdiqhmeh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtjppikwsh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gtftfduwac.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtivbvhedy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtnkeskgnq.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtygkmppzb.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gtfxhhxsan.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtpagnjbqm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gttsgsrlif.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtavnziinu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gthaoowfmk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gttpwkvoao.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gtbevjdieu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gttxlevjwj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtzsbrrhvj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gthppnxgtk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gtgytmobii.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtoegpzxya.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtqntkuvau.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtsuxvqryg.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gtjfwgmkfz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtgmtebtkl.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgivkpufj.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtvtrifhxk.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtlunquqkx.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtievoqksx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtuvqmikux.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtbnmirexy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtvukpqxwb.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtndtwgnld.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtxzmwwkhb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtmlybkgjy.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtoqswycov.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtjkxczcgp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtwxapelcr.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtfqivhvkz.html


<!-- 参考信息 -->