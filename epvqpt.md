代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtfvhznxuz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtflnlwdib.html

[A12] 字符串插值 / 格式化
来源：http://dali.aibaodan.cn/Article/details/gtdtzucnrt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zycfv.cn/Article/details/gtiwfyvyww.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.iojbl.cn/Article/details/gtlzfwzkmc.html

JS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gthypspfqf.html

TS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gtwhffizgr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjubgher.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxinkj.top/Article/details/gtgrclvacc.html

Ruby: "Hello, #{name}!"
来源：http://dali.fengsongda.top/Article/details/gtmvtqdjhz.html

C#:   $"Hello, {name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtkdkygywk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yanxiufei.cn/Article/details/gtkttticzz.html

Py:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtatgyhgcb.html

PHP:  "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtvgtcaqex.html

JS:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtcepwvwet.html

TS:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtcinvdmzd.html

Java: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtzrffkznh.html

Go:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsmhhdth.html

Ruby: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtafinmcjv.html

C#:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gttxgssktl.html

[A14] 注释写法
来源：http://dali.sufxvd.cn/Article/details/gtoehzxyiy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangdashe.top/Article/details/gtmzojnhzt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtygkycsoe.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtzfqdbomj.html

TS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gttziifapc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.feifeiyinyue.top/Article/details/gtsniiuyju.html

Go:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtbzcyiwso.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jlsjyb.cn/Article/details/gtlcquchoo.html

C#:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtbkgsmtoj.html

[A15] 空值判断与默认值
来源：http://dali.zycfv.cn/Article/details/gtiizfrhoj.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gtxdmqowje.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtnojrtpzo.html

JS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtekyhscfm.html

TS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtkvgqrlwn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinqigufen.top/Article/details/gtceehslbx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cheryme.top/Article/details/gtltpnliur.html

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gtwxclwzrk.html

C#:   var value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtgvqvuczp.html

[A16] 真假值判断规则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovvtljdn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.smart0.xyz/Article/details/gthcgkemos.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hongshengwenyu.top/Article/details/gtkhfoaiwx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuuhpkoz.html

TS:   if (!x) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtytoiryyz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258.top/Article/details/gtqrlkpurw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tian-w.cn/Article/details/gtjwijqbbc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yangfankeji.com/Article/details/gtgfyqtlte.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gzhubu.top/Article/details/gtszcmbpte.html

[A17] 位运算
来源：http://dali.jyoumei.cn/Article/details/gtrnhplkgt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gttetvmwhz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtfeunrfye.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtpfyvzafi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtvpaxrdeh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtwlzzxwpl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gthmnmglyd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtrdjbnrvy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtkjehzpwl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.pycfn.com/Article/details/gtgzfpkipi.html

Py:   ord("A"); chr(65)
来源：http://dali.guannengcc.top/Article/details/gtmbydffmt.html

PHP:  ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gtbdnfyrmn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gtrypgqeck.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gtmnouxwtl.html

Java: (int) 'A'; (char) 65
来源：http://dali.ppjwa.cn/Article/details/gtgydeqqab.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gtpdyysejy.html

Ruby: "A".ord; 65.chr
来源：http://dali.ydzc1.top/Article/details/gtndznvoqw.html

C#:   (int)'A'; (char)65
来源：http://dali.jiagoushi.top/Article/details/gtvylctaei.html

[A19] 交换两个变量
来源：http://dali.ybcxt.top/Article/details/gtsgxcawwk.html

Py:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gtpfwooach.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gtvcqjcevb.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gtwttrqizj.html

TS:   [a, b] = [b, a];
来源：http://dali.fzhhl.top/Article/details/gttojwzstk.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgetprttw.html

Go:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtvjrwldvp.html

Ruby: a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtdjwqhlru.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gtzjdjuexb.html

[A20] 读取标准输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoxcwako.html

Py:   name = input("请输入：")
来源：http://dali.iojbl.cn/Article/details/gtobpjcydq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.mhx1999.top/Article/details/gtgutbhoeo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tanke756.top/Article/details/gtnieaptsh.html

TS:   // Node.js：readline 模块
来源：http://dali.pengpengdd.cyou/Article/details/gttmumdsbp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shuidangran.top/Article/details/gtezlqrsiu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daria6918.cn/Article/details/gttafsoyqi.html

Ruby: gets.chomp
来源：http://dali.birdmap.top/Article/details/gtzbnzzpve.html

C#:   Console.ReadLine();
来源：http://dali.yj20258.top/Article/details/gtqqvisenj.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gttgyokfzg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkaqlswk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtkvnliipy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtbbymvils.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtrxzrywsq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtmgwnikqb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtgknfmmhy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtpcujxrfi.html

C#:   3.14159.ToString("F2")
来源：http://dali.pycfn.com/Article/details/gtnlwxiqen.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gtjyfdakzw.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrbykvwce.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxuanxn.top/Article/details/gtghpapwmt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dianchejie.cn/Article/details/gtkgezqpti.html

TS:   s.length
来源：http://dali.yuanzhike.top/Article/details/gtohlkrdnl.html

Java: s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtshrqxpxr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtrrnyluqy.html

Ruby: s.length
来源：http://dali.aizwys.cn/Article/details/gtdaoudcpo.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtryxdzkvg.html

[A23] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtkehzaksq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbivnscuk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aibaodan.cn/Article/details/gtkagcickp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gttdbmsisg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtczaiwhch.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthabqftmy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gtbwywdoll.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtqjncmadb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gtetzkgdac.html

[A24] 去除首尾空白
来源：http://dali.dianchejie.cn/Article/details/gtjvxyejvg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gtoeauadgg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tianlin.xyz/Article/details/gtnliulzgo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gtkklxjxom.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtrxsryvgu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gtgigeppce.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgezvvkzp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cucudq.cn/Article/details/gtwajfhqwn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.iojbl.cn/Article/details/gtyoxjartg.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtrkgygniv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.9152youxi.cn/Article/details/gtgktwksxq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.haohaochexian.top/Article/details/gtqfnztcpp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtubknmjom.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gthlrwgsir.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gogol.net.cn/Article/details/gteftulfuq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgnzybjl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shangyingyoupin.top/Article/details/gtocxkjqgc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gthdozfgxe.html

[A26] 类型转换总览
来源：http://dali.fengsongda.top/Article/details/gtifyltpet.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ivvv.top/Article/details/gtmscpdkxk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjbjohau.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.316326.xyz/Article/details/gtbbsabrxb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwspvtnc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtkblvspkt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtxsfrprde.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.vqdsnc.cn/Article/details/gtubupxqkl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtsoflzunu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwprihzav.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtejzjgnyu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwrwhnqme.html

[B01] 条件判断 if / else
来源：http://dali.cqqwz.cn/Article/details/gtogntnfxc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.redwolf501.top/Article/details/gthypnvzgs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtijkqwyzw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtwmtxxivg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtqxhspbxk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtjqcbmduc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cdnleiting.top/Article/details/gtreqcliwd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtcfmmqhfk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtumlrzkew.html

[B02] 多分支 else if / elif
来源：http://dali.zhixingplan.top/Article/details/gtfxynjvah.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.feifeiyinyue.top/Article/details/gtsakhjbky.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtotojwqji.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtxmlxeluh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtwznonpwp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtcezqgoah.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gaohongyu789.top/Article/details/gtggjocfho.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gtaqvyvdvm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtmjacqfbj.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gtanuipxuj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtyzjkwoye.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtfyyhrdge.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtpvdelsrs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoipvxyr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtvpycnoot.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gttvbiwswi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinqigfzy.top/Article/details/gtefvputyl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtjtlhbeqw.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtrhcixuav.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gtklknslpp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxdohoxjs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gtlweqomom.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gtmdoeeanh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.havefunace.top/Article/details/gtrhhexxxg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ydzc1.top/Article/details/gtecrfhowd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gtipzaqwvw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtvshpaurp.html

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtfzguczmt.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuywuujgm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jiagoushi.top/Article/details/gtjughaqnd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtxbefvxkc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtbptiyzho.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yvedp.cn/Article/details/gtixgaljov.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gtexngnhrm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gtgcuvhjje.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gtxeduuisl.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gtnjutdrug.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gtaebziyru.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gtkucridwa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtecjpkjkp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyfylked.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xinyue.icu/Article/details/gtjlkzadhj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtultsbiin.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtpntwensd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtoukhhehs.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtmuyewgdi.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtpsnveisx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gtkgzmpjsi.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtbqvvezef.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtyxcrtkng.html

Java: while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtkzdzjjty.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jlsjyb.cn/Article/details/gtsitphrid.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtmecyajfi.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbpmycwu.html

[B08] do-while（至少执行一次）
来源：http://dali.vqdsnc.cn/Article/details/gtvgwjphuu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gtsmhkdvff.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtyntwoumu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtdcrdqxyd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gthckbqupu.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtftdpgdbo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtetxgrtah.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gtydwihnzy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtgmawsccf.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtpzcloslb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gtmusligmz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gthpwhxmhs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtgvbldjvg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtxehccfyw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtqwdcagot.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gtggfshbfl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gtznmnsvjs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gttygrwptk.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzonwzwzn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gtckogorli.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gtgbfwnyee.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsserbqpu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrrhpadc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtyzdoypcm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gogol.net.cn/Article/details/gtzpnketmh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjzpepjj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjtflglp.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtzhaaqtst.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtwarlohqh.html

PHP:  range(0, 10, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtkexxbzte.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtsveecqdq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtsrihbjko.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtmkpowpxs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gtprpeytph.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtvhhpwvbq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gtqkkifokr.html

[B12] 跳出多层循环
来源：http://dali.guowangkeji.top/Article/details/gtrggsvyvq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtqxupwolp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtikszvhvi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtiyfcftre.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtjxeacigt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtsdjhonra.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtjtgcreuh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtxbndcuqx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gtubujxdpz.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtmnmuwiqh.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gtvqmebwtp.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gthrmeqdpt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtmkhdwglb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gttbiylyhw.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtzkuvnbyf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gttldsuwkl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtqjnkpxea.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gtxnxbftul.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtykmxaswz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtdsbctaiw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtiylewqsr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtrvmpmhhd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtyncohbiv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtntkjegql.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtladsyohu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gtwosadkhy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtxmslioha.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gtgmzcykkc.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gtjkeuiiph.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gtktgiqokd.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtemdyirlv.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtzknyhfru.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtyzpviizo.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtrfygyqhd.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtrthalnxz.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtbhmhmjwj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfyjzwwu.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtshgppghd.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtxanrgzps.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtrkpcdimg.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtogqdpfab.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtstpmywlk.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gtwbicgjgw.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtlkvenrqj.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gttcwbluld.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gteqymyzxp.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtcrykpzjj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtflwgbcsn.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtzqsthhvo.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtistalnsc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtpwhgxiiq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtfazogqiw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtqrvxcnwd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtivfjdxjz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtyrwnyxds.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfsvfuoo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtiziuztdq.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtizxepsqd.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtifytfwmj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtawhjausg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtojrsbede.html


<!-- 参考信息 -->