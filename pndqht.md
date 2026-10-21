代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtkcetontd.html

[A15] 空值判断与默认值
来源：http://dali.daria6918.cn/Article/details/gtibwtqspl.html

Py:   value = data or "默认值"
来源：http://dali.hnqzz.top/Article/details/gtcwjygztr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtaofsiohq.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtzoteisxc.html

TS:   const value = data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gtjiqvfkpc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sxryk.cn/Article/details/gtqlyxlzin.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigfzy.top/Article/details/gtfslmnqry.html

Ruby: value = data || "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gtbllnnohx.html

C#:   var value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtfipekjts.html

[A16] 真假值判断规则
来源：http://dali.c1oappe.top/Article/details/gtbpzspluv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhixingplan.top/Article/details/gtjvpxyfwr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.havefunace.top/Article/details/gtktohagjz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guannengcc.top/Article/details/gtamjvzuyz.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gtvjwrrwut.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cdnleiting.top/Article/details/gtrljpxvgo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmpfgogq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xylfe.cn/Article/details/gtsdumhtoe.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtudpymtgy.html

[A17] 位运算
来源：http://dali.guannengcc.top/Article/details/gtwcxcapcg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtpcugbxko.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtfblibwpz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtnrwaqzob.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtwvohhzev.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtcukyppbp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtunfqachd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtqkyfzgun.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtwoszfjzd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jlsjyb.cn/Article/details/gteagdoffw.html

Py:   ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtoaitwydp.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gtuqqazelt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gtutdibkvz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj202588.top/Article/details/gtvpdjhfev.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuanzx.com/Article/details/gtmhsctmad.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258.top/Article/details/gtpfqyxrmt.html

Ruby: "A".ord; 65.chr
来源：http://dali.yongpay.top/Article/details/gthmuvttnr.html

C#:   (int)'A'; (char)65
来源：http://dali.quarkkingdee.top/Article/details/gtbfbhaaos.html

[A19] 交换两个变量
来源：http://dali.ydzc1.top/Article/details/gtidunisnt.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdjzhtak.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ivvv.top/Article/details/gtvqjmkvrt.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gtkolceycm.html

TS:   [a, b] = [b, a];
来源：http://dali.iojbl.cn/Article/details/gtttomoyfh.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtrjkecasf.html

Go:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtkggfrycd.html

Ruby: a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gtjzemusck.html

C#:   (a, b) = (b, a);
来源：http://dali.sysykeji.top/Article/details/gtrhkzcwfj.html

[A20] 读取标准输入
来源：http://dali.yongpay.top/Article/details/gtxsnxgqsj.html

Py:   name = input("请输入：")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzwvzaya.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.0kj1m.cn/Article/details/gtwiekdhbp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhixingplan.top/Article/details/gtrwgfbfda.html

TS:   // Node.js：readline 模块
来源：http://dali.sufxvd.cn/Article/details/gtbxwjhyaf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xuetiantiany.cn/Article/details/gtasetxokv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sysykeji.top/Article/details/gtapudaxgo.html

Ruby: gets.chomp
来源：http://dali.cdnleiting.top/Article/details/gtezeuchrq.html

C#:   Console.ReadLine();
来源：http://dali.snrcjt.cn/Article/details/gtrmawvjjt.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gtrlztjrgc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.snrcjt.cn/Article/details/gtdmfviuqc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtqwbtzcmr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtkkxfaojc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtvhznowxi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gtnkkfhbcp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gthqxzliaz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtktbkypgp.html

C#:   3.14159.ToString("F2")
来源：http://dali.ehwqpu.com/Article/details/gtzctlbton.html

[A22] 获取字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtsozswixc.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtipfuwsed.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dianchejie.cn/Article/details/gtsafelirb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gtcikwgfug.html

TS:   s.length
来源：http://dali.cucudq.cn/Article/details/gtxfpnfggp.html

Java: s.length()
来源：http://dali.sysykeji.top/Article/details/gtgxinhopv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ydzc1.top/Article/details/gtnnhtkiqz.html

Ruby: s.length
来源：http://dali.meibo888.top/Article/details/gtjxbfryfg.html

C#:   s.Length
来源：http://dali.daria6918.cn/Article/details/gtqbxerrdx.html

[A23] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtvevlebqo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbitafky.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gotoacloud.top/Article/details/gtfikmcpjg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gttzsivjtd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtckcdgvqr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gtiqxajxni.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtyazwbpcu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtbrhjfcxs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shangyingyoupin.top/Article/details/gtvorvdtdn.html

[A24] 去除首尾空白
来源：http://dali.quarkkingdee.top/Article/details/gtxpmtbytb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.iojbl.cn/Article/details/gtgjcfcnbk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gtsvagspyp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guannengcc.top/Article/details/gttsnjbmru.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtopqlivbl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shuidangran.top/Article/details/gtkykvqzzi.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxckeipxq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hfpthk.cn/Article/details/gtmmsffhyp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.bjfxy.top/Article/details/gtjinsgbst.html

[A25] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtjowzfhvr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gzhubu.top/Article/details/gtlvugbaxs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shuidangran.top/Article/details/gtlgczbsyw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gthzvpzbia.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gtcadzqqwk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtptyoxmoj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxlwvyrr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ehwqpu.com/Article/details/gtqnnoqtso.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gthjjnzvea.html

[A26] 类型转换总览
来源：http://dali.chenlongwang.top/Article/details/gtronnjrxu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xziqi.cn/Article/details/gtjbxqwdcy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aibaodan.cn/Article/details/gtyqxmdntc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shangyingyoupin.top/Article/details/gtcfuzmwfq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ybcxt.top/Article/details/gtaswmmltz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtlomoqfrx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuetiantiany.cn/Article/details/gtfhzvamtw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tanke756.top/Article/details/gtzqvrcggg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgdnaqab.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtuumfabrk.html

B. 流程控制
来源：http://dali.jqgufenzy.top/Article/details/gtczczxnpv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfvcisgih.html

[B01] 条件判断 if / else
来源：http://dali.tian-w.cn/Article/details/gtdlktjlsx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtkcvjleet.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cdnleiting.top/Article/details/gtqlkfmrep.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtgvhsnllp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gttshgteac.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gteonxtyej.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jyoumei.cn/Article/details/gtuyhsqgtc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yanxiufei.cn/Article/details/gttsyzbgea.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtriqsmvtg.html

[B02] 多分支 else if / elif
来源：http://dali.wangshuangyany.cn/Article/details/gtpsugbqgl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtudewnvgd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gtdutiqotf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtziichcnx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtpjbqeecj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtwqbvfnei.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gtclecacnz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pengpengdd.cyou/Article/details/gtytigtxcf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtlqthxfup.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtejnxxvjg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwqqyzev.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtslcjnbyr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtfcqajfqh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbntzisll.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtanxipssz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtgweuxnsb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hywenlv.cn/Article/details/gtbhmttbec.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtxuceymzd.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtlxcbnkmw.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gtldaqelde.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tianlin.xyz/Article/details/gtoglzflgo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtnsycnghh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtndqengwl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sufxvd.cn/Article/details/gtpujwbwsx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gtqsyfnfbg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gteisozryn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtgnmladth.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrydzjppe.html

Py:   for item in arr: print(item)
来源：http://dali.jqgufenzy.top/Article/details/gtzgmgyugy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ivvv.top/Article/details/gtwvwljvyd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gtbagihrbc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtboqjwzjz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gtrwikrwvg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gtrltcvdch.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtimgwlgcv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gthrcabrib.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gtubikuiqn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.feifeiyinyue.top/Article/details/gtpzjscuyn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtowgxpedf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtqviafmcq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtwrzyymwy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlpeiitrk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yanxiufei.cn/Article/details/gtxubhnpjj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gtiigjakxz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojoleumd.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gttfsxryeg.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gtafvbydpc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzzlzhve.html

JS:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtbwgczcsc.html

TS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtjybcdvwk.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtfzfgtmhj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gtaiepgkwj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtshdipsgq.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtwmqibpxu.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gtoitsohbg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtwxgazizs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fengsongda.top/Article/details/gtduamitrs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gteseqyayk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtsopmrhml.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtqdyralhz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xinyue.icu/Article/details/gtczneyelz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuetiantiany.cn/Article/details/gtbkzzohjq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtapqirdrt.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtpqwcpenr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenzaomai.com/Article/details/gtafmqlety.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtmjsnkckx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtcnigbbuw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtdrzsxspe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtcoodogyw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gtluoubwza.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hysaishi.cn/Article/details/gtckopicsj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtitgpxycj.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gtmeglwdvy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtspjfeatt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cheryme.top/Article/details/gtxbbtpmgq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtobdqpnnj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmyzzyiz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqizaubws.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gtxqcxwjmy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gtbwrrlslw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gthydbhagu.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtfnixqexf.html

Py:   list(range(0, 10, 2))
来源：http://dali.jianghu66.top/Article/details/gtaxcdmivm.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtbxsocbwt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gthrfylilj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtimcwjyxw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtzfrawufd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gtvnswcfrl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtbosunrzr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzdfajfj.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gtakcxlktu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gthrhiiavt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gtodpkozzj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtzzwrznrb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtbmbctwyz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtbhdqiqyg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtqfbppwgx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gthgciscfy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gttfqduwld.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gtihoatotj.html

Py:   isinstance(x, (int, float))
来源：http://dali.sweek.top/Article/details/gtxviwsmji.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtvfatwbjt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtyzsshetk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtkymqzkyd.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtfitwsiyp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtakamimti.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccbsusgi.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gtpptzwbnl.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtwlgistah.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtagdcrmyw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gtldrqprcu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtuohahgzk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduwnsjku.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gtkzkjlmjt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gtmjdmatqd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwavzlwb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtcnaliomn.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtbvacbjoh.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gtvdiiwzmp.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtcytmfsvs.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtxeaatmjg.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtnkllfndg.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtvjuvsluq.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtfbfjroqu.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtjwgkqrvt.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtuholtsgh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gtxbzqtyed.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gtkptwqrks.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgfzy.top/Article/details/gtqrmdkwti.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtarshvlws.html

TS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gttcosfjjg.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtbftbhtye.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gtcsxunqto.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtxzbnvaiv.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtqrnggebt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtijupunyv.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gtvkvnspvu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqrmgdvaz.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gttcdjbgbf.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gthbzhjzzu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gttxgiclvt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtwrvmrgou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtbyxkadhq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtvlswuvef.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gteeyfauzx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtxmirxfqi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtzhiyrcwf.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtbtgtgkjb.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gtbvbhnaas.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gtzzxivasz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtsdbpwtwz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtivysuupw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtdsoeuccc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gteoqduypp.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtzrhtrwkp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gtdxyevwlm.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtydsigxkq.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gtihbkbcbh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtopqswbxg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtfvsyytcv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtqbqveyxr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gttlxqsaiy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gteqcfpezw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzznvimhp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gthkndnzvx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gtxtaypvbx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gtxswyqrec.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtveqxuphv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtncywtlzr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtpccvydjr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gtwymzxtjq.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gtxfgjvixk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtxkdkqwau.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gthvxrsipk.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtzsggwndw.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoivjcbcy.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtsvmhgcdf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtwkhawics.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtnlpvpuxa.html


<!-- 参考信息 -->