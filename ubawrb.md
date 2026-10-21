代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sufxvd.cn/Article/details/gtcoqbqehz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hfpthk.cn/Article/details/gtrruxxolo.html

TS:   if (!x) {}
来源：http://dali.zhixingplan.top/Article/details/gtmnnkmoea.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.daxiang520.top/Article/details/gtqrodbtkd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenzaomai.com/Article/details/gtllwswjya.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gotoacloud.top/Article/details/gtfbqcqfey.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtugrthhvy.html

[A17] 位运算
来源：http://dali.shangyingyoupin.top/Article/details/gtmjaxnykm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtcrbfdqna.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodpqbpyg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtfjxmdnii.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtucspzwvv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxqmxfwd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtoxrnlavi.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtlieruvsj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtibvzhkmb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guowangkeji.top/Article/details/gtttgaxnoh.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gtogukiayi.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjkfktvm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gtqsjeohxu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gtrrltodnn.html

Java: (int) 'A'; (char) 65
来源：http://dali.meibo888.top/Article/details/gtzjusural.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zycfv.cn/Article/details/gtyuyfzsys.html

Ruby: "A".ord; 65.chr
来源：http://dali.fzhhl.top/Article/details/gtabaopdel.html

C#:   (int)'A'; (char)65
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbobhupwa.html

[A19] 交换两个变量
来源：http://dali.feifeiyinyue.top/Article/details/gttfgezrwe.html

Py:   a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphsakgha.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.mhx1999.top/Article/details/gtnnprnqrt.html

JS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gtjqdujpdg.html

TS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtrifwonqa.html

Java: int t = a; a = b; b = t;
来源：http://dali.zycfv.cn/Article/details/gtrwsdwopv.html

Go:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtdqpulhyf.html

Ruby: a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gtougokkfv.html

C#:   (a, b) = (b, a);
来源：http://dali.sweek.top/Article/details/gtqhqjpkwo.html

[A20] 读取标准输入
来源：http://dali.jinqigufen.top/Article/details/gttijsvpgo.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gtajwytmih.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xziqi.cn/Article/details/gtxqjkmrlg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cucudq.cn/Article/details/gteamrcxav.html

TS:   // Node.js：readline 模块
来源：http://dali.ppjwa.cn/Article/details/gtbctdomzc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tianlin.xyz/Article/details/gtxajgmmri.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuanzx.com/Article/details/gtfnnuumir.html

Ruby: gets.chomp
来源：http://dali.ybcxt.top/Article/details/gtmytkoxob.html

C#:   Console.ReadLine();
来源：http://dali.9152youxi.cn/Article/details/gtltcgzdei.html

[A21] 保留指定小数位输出
来源：http://dali.sweek.top/Article/details/gtcyuzzzoi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gtrezxvbiq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtazolcdfu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtjqyjssws.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtjghjldkg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtxcymbdey.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtpthzdwpn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtxltapwsv.html

C#:   3.14159.ToString("F2")
来源：http://dali.ivvv.top/Article/details/gtzhgwtwxg.html

[A22] 获取字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtowpkqwef.html

Py:   len(s)
来源：http://dali.hammf.cn/Article/details/gtrlnbpwkl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ppjwa.cn/Article/details/gtwhpsvyua.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cqqwz.cn/Article/details/gtclsuoaux.html

TS:   s.length
来源：http://dali.xuanzx.com/Article/details/gtntfrybko.html

Java: s.length()
来源：http://dali.tianlin.xyz/Article/details/gtmlemchsx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dianchejie.cn/Article/details/gtjuxxffns.html

Ruby: s.length
来源：http://dali.daria6918.cn/Article/details/gtorjcxlly.html

C#:   s.Length
来源：http://dali.zycfv.cn/Article/details/gtpvxzjyxs.html

[A23] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtrbnraxus.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.mhx1999.top/Article/details/gtswahigyu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgfzy.top/Article/details/gteiftrfnc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtjhbjawtg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtcoxmjbqf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gtgvphkhaz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hywenlv.cn/Article/details/gttqjyjgeo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtsmsrvqqm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gogol.net.cn/Article/details/gtogqkzmfk.html

[A24] 去除首尾空白
来源：http://dali.kuanghao11.cn/Article/details/gtjghnsugi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jlsjyb.cn/Article/details/gtnpmzvqib.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zdqjudy.top/Article/details/gthiownive.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtncytvhqk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtcglwabqn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hammf.cn/Article/details/gtsyxarkhq.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuxming.cn/Article/details/gtzwlrvzzx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.316326.xyz/Article/details/gtoyvdlmqf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtaycfhlzz.html

[A25] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtubghhnni.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tianlin.xyz/Article/details/gtctlygrvp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhixingplan.top/Article/details/gtdxzjovyy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gtzimuudtm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtheezyygf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtpmmoigzg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gtyyekblsq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xylfe.cn/Article/details/gtlcsiwrtf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aibaodan.cn/Article/details/gtwszbafya.html

[A26] 类型转换总览
来源：http://dali.zhoulong.xyz/Article/details/gtvnvytpow.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gtbzrftwfa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ydzc1.top/Article/details/gttbhajzoz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daria6918.cn/Article/details/gtclogtybe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nwbrower.top/Article/details/gtlgpywxvr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gtdqkwifts.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtanzbimpl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daxiang520.top/Article/details/gtfndziorb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtlspitukt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtszosnijp.html

B. 流程控制
来源：http://dali.zhiwuduotai.top/Article/details/gtdcjeftkf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvfnzsnav.html

[B01] 条件判断 if / else
来源：http://dali.zycfv.cn/Article/details/gtwhevdwno.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gtphcakwts.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtdeihfuwj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtojjngshy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtvgztoxqz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtxcssmacw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ppjwa.cn/Article/details/gtihxsavzq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtgkaeczpd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtcrfliizo.html

[B02] 多分支 else if / elif
来源：http://dali.cdnleiting.top/Article/details/gtoxrtjhrt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtazxtwlmo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pycfn.com/Article/details/gtcwedvfeq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtfrcikwbm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtdpwthxqx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtjumsgyln.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuldabls.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gtzimowloy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtbzgfvxjg.html

[B03] switch / match / case
来源：http://dali.smart0.xyz/Article/details/gtqzsdhybn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ivvv.top/Article/details/gtjkvgrkfu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtjwuddouy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtxjsxdaqc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtahabbqss.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtscgzpwyp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtvgtzouyh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nwbrower.top/Article/details/gtzyjxnazm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.meibo888.top/Article/details/gttfzubged.html

[B04] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtxzeicuyu.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gtsrhxdgqf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gtkxmkvrqa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gtstsuzpep.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtfmriitbf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtylmozqyq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gtjekydlxh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtdrfmuccw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtcjygliez.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtvdmrjyuu.html

Py:   for item in arr: print(item)
来源：http://dali.zycfv.cn/Article/details/gtbdbillwu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.9152youxi.cn/Article/details/gtmybebbxd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtcswtscid.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtawgaibmb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtzdduieyp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.birdmap.top/Article/details/gtaaycoyoo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuanzhike.top/Article/details/gtipixzvqe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtvowhtonh.html

[B06] 遍历字典 / 对象
来源：http://dali.sysykeji.top/Article/details/gtmnahczub.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tianlin.xyz/Article/details/gtjdafveuo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gtlbywqdff.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtlzhpekiu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gtrrtrsfcc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gtcjanvvoz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gtkxhpwulj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtqneiiiev.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shuidangran.top/Article/details/gtrufmspau.html

[B07] while 循环
来源：http://dali.jyoumei.cn/Article/details/gtizwswvbp.html

Py:   while i < 10: i += 1
来源：http://dali.nanxuanxn.top/Article/details/gtrqzrmgou.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtwjphtotw.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtemlzzckz.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtvykodimy.html

Java: while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtirsedzbs.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guannengcc.top/Article/details/gtogygqodl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gtqpotixec.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtcqtwqejf.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gttklshgbf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gtsfyoxkje.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gtsugbbmtt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtvoqmygkj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtczlcdeyd.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtunfpknhn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtnjthqihc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gtaenhovip.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtyrjobvbf.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gtpawlgjlq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtzavftkzg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtolnfsbhm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtrjtrxzco.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtnxplpxjo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtfkhkynsy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtnughzwkn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtqaqyurdv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gteerfannp.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtovnbwonu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hfpthk.cn/Article/details/gtptkqqylb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gtgzownfsy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gtzfoqcasr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtheuttbuh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gtnujuvbpi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtdltruolp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gtbsdecszh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmfcnlqh.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gtfmyhtllr.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gtyllnpwku.html

PHP:  range(0, 10, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtwfwmfrzh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gttbyshwzr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtvvdkeoue.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtinihqcgy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtovfeejfz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtvclosxlk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtnredvsml.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtuhqpphnv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkngrgwxq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsheacvy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjymahnft.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtbzzsglio.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtjllrrhzg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gaohongyu789.top/Article/details/gttnwpflph.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtjzwixvxw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gtizgnhokv.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gternwxxia.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gtskyzrodk.html

PHP:  is_numeric($x)
来源：http://dali.nanxuanxn.top/Article/details/gtdtoyibpi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtuumymvjq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtbyeqcueg.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtypgntffv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gtejpofbyj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtdwrlclcm.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gthpqrvbsd.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gtgewjejcm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gtrvptvhro.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtuyvpiaes.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtawoegupb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtmmjkfuso.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gttuakiarx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpayrfugf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gtagssehki.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtavmqjfsw.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gtzlosgnig.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtvwtyzzfi.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtyokdjabq.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtwtwfdwgm.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gttiwywsoj.html

Java: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtjfmpvfae.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtewqsrmcj.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtuspzzrii.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gthzfoarta.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcswsfusp.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gtqqvuqals.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtkhmyeckz.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppxzovef.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtpgrrnbbj.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtkzyjfmod.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtffguznjl.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtueqagubl.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtxhcefqib.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwawndcmv.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtyutnazts.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhtbhzjl.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtfwtdwhqw.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtrxarufoj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtafhdvtgf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtiaptpcef.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtbnzpgyaw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcgctukf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtinfomxuk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gteocarqze.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtznosruxf.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnumxykm.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtjgefsjso.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtdrtdqloq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtclifrilc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtznioiztb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gtrkbcnjhe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtajozrmhi.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtlrikjlll.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtduamcngl.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtreoihkxu.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvppofmpu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtmuurrxvt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtkymqsreg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtfmxxbqbe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtlabykeof.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gtrjvmptfn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtgxbctdfi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtkcfkmzoy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtcnffcjdn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtjpqtuucy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gturoklsfu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtsxsfnknk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtargetnyk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gttkzzqtee.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gtalkfvmwg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gthptwyidu.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtfimiofno.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtvwvpoodm.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtpjffogjw.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gtrpzdnswi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtgkqlwcvt.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtnzuuqjxx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtvtgyiids.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtrygkldqm.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtjldgdcrz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtluepqvpr.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtxusndlel.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gtdittudek.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gtfoklqumz.html

JS:   const square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtacdrgpsa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gtrkwrcgtc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpmxcwde.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtjqfcpztb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gthnlexnar.html


<!-- 参考信息 -->