代发 wailian999

[A14] 注释写法
来源：http://dali.ppjwa.cn/Article/details/gtzcivyesb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gtupbilntj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtjnenicmp.html

JS:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gtbjfloyyo.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtjbahwwkl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj202588.top/Article/details/gtynwnrvxf.html

Go:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspjfyuyi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cheryme.top/Article/details/gterxohdrs.html

C#:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtienwffbs.html

[A15] 空值判断与默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtnbncrmck.html

Py:   value = data or "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtjcukxdur.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtuiqzmoyn.html

JS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtrahfiupl.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtjouofmlk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvhdgtvd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangshuangyany.cn/Article/details/gtvrmsurtj.html

Ruby: value = data || "默认值"
来源：http://dali.fzhhl.top/Article/details/gtlsnbfwio.html

C#:   var value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtqarkquqh.html

[A16] 真假值判断规则
来源：http://dali.cashguo.top/Article/details/gtswjfpeog.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtynjfcfsx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dashuyun.cn/Article/details/gtuqahkyfi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gtgjozftky.html

TS:   if (!x) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkvhvhxes.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fengsongda.top/Article/details/gtieualyqr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gaohongyu789.top/Article/details/gtjfwvzadh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258888.top/Article/details/gtkjxcehaa.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwfvlarpc.html

[A17] 位运算
来源：http://dali.havefunace.top/Article/details/gtgjhvugci.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtlglfqnlg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtqnzzvepl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtdbfwvhhs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtpmodsgok.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtmjdnyzes.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gttyvcekky.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtyjiwfowg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtxbrktpaf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shuidangran.top/Article/details/gtqunwvace.html

Py:   ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtshsrhczf.html

PHP:  ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoprbnlat.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aibaodan.cn/Article/details/gtazhmtlqq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aibaodan.cn/Article/details/gtucyzwalv.html

Java: (int) 'A'; (char) 65
来源：http://dali.cdnleiting.top/Article/details/gtmrtxgqhx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.quarkkingdee.top/Article/details/gtmonlgrsq.html

Ruby: "A".ord; 65.chr
来源：http://dali.meibo888.top/Article/details/gtaqrxtzfq.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gtxnsulptn.html

[A19] 交换两个变量
来源：http://dali.jinqigfzy.top/Article/details/gtktkqsdhj.html

Py:   a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gtezaxdexr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrgpvdov.html

JS:   [a, b] = [b, a];
来源：http://dali.chenzaomai.com/Article/details/gtqaykuvov.html

TS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbtbxgqg.html

Java: int t = a; a = b; b = t;
来源：http://dali.xylfe.cn/Article/details/gtxwifnqgm.html

Go:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtdibvyxnr.html

Ruby: a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtnmfjujhp.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gtyetizbic.html

[A20] 读取标准输入
来源：http://dali.andypj.xyz/Article/details/gtcnxxqent.html

Py:   name = input("请输入：")
来源：http://dali.cashguo.top/Article/details/gtrkohhfcf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gogol.net.cn/Article/details/gtzbfixlce.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pycfn.com/Article/details/gtsogfxvso.html

TS:   // Node.js：readline 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtekdhbpsu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aibaodan.cn/Article/details/gtiybywjce.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgfzy.top/Article/details/gtavfcdwxp.html

Ruby: gets.chomp
来源：http://dali.xinyue.icu/Article/details/gtcqerekfa.html

C#:   Console.ReadLine();
来源：http://dali.ehwqpu.com/Article/details/gtujldluju.html

[A21] 保留指定小数位输出
来源：http://dali.tanke756.top/Article/details/gthaquzdmn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoezuuxfp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gthgpeunqa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtlvnwakux.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtvbjqafle.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtwhynquhp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtfpsbilso.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtckvhbeit.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gtywlicgst.html

[A22] 获取字符串长度
来源：http://dali.yongpay.top/Article/details/gtipatgfdr.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtssmkmzhf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fengsongda.top/Article/details/gtyinzfqda.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258.top/Article/details/gtpyqrrbgw.html

TS:   s.length
来源：http://dali.cheryme.top/Article/details/gtcrkdxhdv.html

Java: s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggdfqruv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fzhhl.top/Article/details/gtddrghuuh.html

Ruby: s.length
来源：http://dali.ydzc1.top/Article/details/gtvobxvqqj.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gtlovunzjw.html

[A23] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtnoryploi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtjpovspfb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guowangkeji.top/Article/details/gtygepffzp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtfykotwcr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtalastxsy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtgxnzhcwg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shuidangran.top/Article/details/gtmzzcwsyf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtzvmylcjt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cqqwz.cn/Article/details/gtlwhazkax.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gtyybxlirc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dianchejie.cn/Article/details/gttvjsmqxs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj202588.top/Article/details/gtqugeghjq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guannengcc.top/Article/details/gtwxniebdv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxjwfnjm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.316326.xyz/Article/details/gtnwztkbjy.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gthggfzgvk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jyoumei.cn/Article/details/gtaabbuvii.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zdqjudy.top/Article/details/gtvhecxyiu.html

[A25] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtsqbjxjlk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.bjfxy.top/Article/details/gtvbelmbgf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gtdpgzbypk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gtxbrycixm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtnynsfbij.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtgyfuafnt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrxgqyit.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gtiyjboaeu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtxalmrazg.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtevxgdoif.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gttmnuflwu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pycfn.com/Article/details/gtqohfquhl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.iojbl.cn/Article/details/gtvpknixwx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aibaodan.cn/Article/details/gtpkpkopmx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdrflzfb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gtdwlagmsj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtnkcentpr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtwavwrrrg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtixonzefe.html

B. 流程控制
来源：http://dali.kuanghao11.cn/Article/details/gtvnkbbkso.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrofgpmzh.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gtztkqripf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtctkzziij.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gtmfuncpbc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtqhzzbvss.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtohfhljau.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtpsvqfbpv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtkcolvneu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gtlhbzzpqb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtkdurfqbz.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtnaxhuaoo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnqzz.top/Article/details/gtsobffpto.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gttouepvbl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtbgzjcqed.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtmvltnwvo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtvfwpnank.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hammf.cn/Article/details/gtljxjoriu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gthccsdgus.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanobmctu.html

[B03] switch / match / case
来源：http://dali.gzhubu.top/Article/details/gtcbtukvbk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgufenzy.top/Article/details/gtwkdnyrit.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtqeqiyiwn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtcuoupxbf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtpydcumiq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtekpeqqvs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtyzowaxcd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sysykeji.top/Article/details/gtjhmznvzp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtlxnzxhxr.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtcjjuqmkb.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gtsoaoyzde.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gtkcuxayor.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtyknxgnpq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrebkkps.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtbpmzozhe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gtmxwdmxcn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.birdmap.top/Article/details/gtmnzktlht.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gtubwawuyy.html

[B05] 遍历数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtgmqlwqrh.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gtdegcuyry.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zdqjudy.top/Article/details/gtdmdgmbiw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtmxjsiyhx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gtujynipru.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gtsqhebeks.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tanke756.top/Article/details/gtiehktape.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtxszezuea.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gtaahnywgi.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtwqefwnqt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gtcttabyic.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtstlwihzz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtsluazbft.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtcfsavwly.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtngpfzzfx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhixingplan.top/Article/details/gtiopckxgy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gttesgcewy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtanwbesle.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtnonlxalm.html

Py:   while i < 10: i += 1
来源：http://dali.nanxuanxn.top/Article/details/gtykaqjnvu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gtgkfmoybs.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtvbsydqia.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtaduzewic.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtqxrqadlj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gtjdbiuypk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzenugib.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtwbcyzepp.html

[B08] do-while（至少执行一次）
来源：http://dali.xinyue.icu/Article/details/gtzenrqlvv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gtlknpzwsn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtrlhddwwj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtyhmxxrsb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtczwbhyrv.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtkrfecafm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yongpay.top/Article/details/gtgmmdswfw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtukfupubg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtnperuvgb.html

[B09] break 与 continue
来源：http://dali.dashuyun.cn/Article/details/gtbwskxqbc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sweek.top/Article/details/gtsjjseuiv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtmjspipwt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtnbbhjrin.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtmcejkymp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtefenvjzc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtsddlknqt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gthrcuphlz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtlcllizki.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gtalohhaaz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtsctbagfy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtlnglxeyl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtkqfufgyk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtqorhvhwk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.quarkkingdee.top/Article/details/gtdsduarfs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtdtrmmfwa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gttxrfhcru.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gtpbegvqzl.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gtbivcjmnd.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtcpcvbgjz.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtxjztvfwg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gthjxoiqle.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtxmtcjkgp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.bjfxy.top/Article/details/gtwxmgbapb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangshuangyany.cn/Article/details/gtspafpbbf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtiudxlndt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gthhpslxsl.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtsefgfzok.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gtinehwjwi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtcswlqezw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtgwnduinv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtajyosoqh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtcdgylwiy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gtwmulpznr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gtblguzsyq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gthslxzyks.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtrvbqqkff.html

Py:   isinstance(x, (int, float))
来源：http://dali.bjfxy.top/Article/details/gtmhlpqsbt.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtudrwlbbr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtgokpyoxi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrzcurssi.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtaclenoep.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gtgncbmepz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmztqwtg.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gttrczkbju.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtfctrnygs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtalsujiig.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gthzkukhfa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtjbyugggv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtevvjeitf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtdqfzzrdi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtjpyeccuz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gtawneschu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtevfrcdzq.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gtmezrlhnh.html

Py:   a and b or not c
来源：http://dali.ivvv.top/Article/details/gtuejnulis.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtwbnlylzq.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtclbfeqbc.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtnaffnqsq.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtioyvbrpb.html

Go:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtpegmmitc.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gtmfzajmvz.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtkdmqvqtr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtyijeycjk.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtmqujmfcw.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gthztozpas.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtshuyfxde.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtwwmjwfsm.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtsoozzzee.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtospcogas.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtsikiljbj.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtywtdhgfg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttbzhkkqf.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtxvbixgep.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjjwrpsbr.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtidpzizay.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gtqwldvgpb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gthqlhmifh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtrvwybqby.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtbawfolpn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtpadgcjfj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtzvbnjtck.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gthhctslkx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtuwylrqmv.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtnlwcwhpq.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtrczagwky.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtgnsoeozr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtamugqmmi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtavfqgwti.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtspwteali.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpjbgrif.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbovvnxxp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtckglmziu.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gtkrmdupxe.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gtyiubnatt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gtjymsxacd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuladhesf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtbxrwrihm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gttvotxiqy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gtoxvkkmmp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtznybfpbm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtxptxhtsf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtyyarrtuy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtvttdyykj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtnwsaxxfn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtuwbtdxgl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtccfxcmox.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtiycwrfxm.html


<!-- 参考信息 -->