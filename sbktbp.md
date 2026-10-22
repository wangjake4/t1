代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.9152youxi.cn/Article/details/gt2mjgwsejh.html

JS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gt2gycgznfn.html

TS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gt2sdjqzdhz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yonumen.top/Article/details/gt2yyexgnjv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puauohsz.html

Ruby: "Hello, #{name}!"
来源：http://dali.c1oappe.top/Article/details/gt2grafhspq.html

C#:   $"Hello, {name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsybzxpj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yj20258888.top/Article/details/gt2pvvwnyjs.html

Py:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2mmssiysd.html

PHP:  "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2dizjnuxl.html

JS:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2mlesgsfa.html

TS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2tlvhdpdn.html

Java: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2ahqgbaaa.html

Go:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gt2tqkgmoiw.html

Ruby: "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2opnrwaal.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbtxsbek.html

[A14] 注释写法
来源：http://dali.gzhubu.top/Article/details/gt2lfcjsqvu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258.top/Article/details/gt2yypztgjs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gt2zmnhldnv.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gt2faxxbpic.html

TS:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2xpenmjzu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jyoumei.cn/Article/details/gt2kiuvbkst.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gt2hkhssxxe.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gt2ktyvvqth.html

C#:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gt2rlfadhti.html

[A15] 空值判断与默认值
来源：http://dali.jiagoushi.top/Article/details/gt2ljwskngx.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gt2gnpkxynf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gt2euapnzio.html

JS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gt2idedzfds.html

TS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twlrmatq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sxryk.cn/Article/details/gt2adsvmqsm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cashguo.top/Article/details/gt2zstycmom.html

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gt2djuldyqn.html

C#:   var value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gt2wnxszhui.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gt2zrsjhglx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2aqjotsdd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shangyingyoupin.top/Article/details/gt2woavanmo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gt2tftmndin.html

TS:   if (!x) {}
来源：http://dali.wangdashe.top/Article/details/gt2znxfjdti.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjzanahi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gzhubu.top/Article/details/gt2iygeitlp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmjjugtf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2yipttjvq.html

[A17] 位运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwayppvk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghraffyn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2jpjitzmi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2pqhgilhb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ckwafnwu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzfojtpv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2kyeocnzb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2exkxyzsz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2gborjlbo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gt2ttsisgdr.html

Py:   ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gt2jipzqnpj.html

PHP:  ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gt2hcrarruc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2ytzxnycs.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvjsibtk.html

Java: (int) 'A'; (char) 65
来源：http://dali.aizwys.cn/Article/details/gt2smcbxnbt.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tanke756.top/Article/details/gt2onetkuuv.html

Ruby: "A".ord; 65.chr
来源：http://dali.xinyue.icu/Article/details/gt2rytbwjam.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gt2hkrlnsvm.html

[A19] 交换两个变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfdskzyr.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gt2izmluxom.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gt2yprxufmh.html

JS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gt2avwcxikz.html

TS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gt2ufqpznwz.html

Java: int t = a; a = b; b = t;
来源：http://dali.pycfn.com/Article/details/gt2qplovsjm.html

Go:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gt2jimcbsvf.html

Ruby: a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gt2zzpnptmr.html

C#:   (a, b) = (b, a);
来源：http://dali.xinyue.icu/Article/details/gt2thltzgpg.html

[A20] 读取标准输入
来源：http://dali.jqgfzy.top/Article/details/gt2bdhvyavz.html

Py:   name = input("请输入：")
来源：http://dali.gaohongyu789.top/Article/details/gt2tnguuxsy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guannengcc.top/Article/details/gt2zoxelxvx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xylfe.cn/Article/details/gt2sjwhjoie.html

TS:   // Node.js：readline 模块
来源：http://dali.jiagoushi.top/Article/details/gt2zwoygctt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tianlin.xyz/Article/details/gt2uaejdrxq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.birdmap.top/Article/details/gt2tcsxhpqt.html

Ruby: gets.chomp
来源：http://dali.zhoulong.xyz/Article/details/gt2nkmmwbjt.html

C#:   Console.ReadLine();
来源：http://dali.vqdsnc.cn/Article/details/gt2qvryyspk.html

[A21] 保留指定小数位输出
来源：http://dali.gaohongyu789.top/Article/details/gt2wivtwqjk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenlongwang.top/Article/details/gt2slbpombz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gt2wrmumrvg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gt2hfbkppvm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2sowiclag.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gt2eqgrmoea.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gt2czizqscy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gt2kolsewoe.html

C#:   3.14159.ToString("F2")
来源：http://dali.snrcjt.cn/Article/details/gt2bubhirxk.html

[A22] 获取字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2spgxzowg.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkvclhvw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tanke756.top/Article/details/gt2xzghqgre.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fzhhl.top/Article/details/gt2ycxccjve.html

TS:   s.length
来源：http://dali.hfpthk.cn/Article/details/gt2puuerfwl.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gt2coznhpvf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tanke756.top/Article/details/gt2qaicntod.html

Ruby: s.length
来源：http://dali.316326.xyz/Article/details/gt2sdlxpany.html

C#:   s.Length
来源：http://dali.yueranfly.top/Article/details/gt2psdozyvp.html

[A23] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2nvwdogho.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sxryk.cn/Article/details/gt2kgtfaqjm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.havefunace.top/Article/details/gt2xvjkatbg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2rsqytwvc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuqabyvq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gt2bjvrrzhx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.c1oappe.top/Article/details/gt2mydfznvl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2gnpkopvk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aodvukam.html

[A24] 去除首尾空白
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvvsrald.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.guowangkeji.top/Article/details/gt2elvtvsdk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gt2oruqqqmv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gt2xnqmxdlr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gt2gddnpifd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gt2knwlmlkl.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gt2kypkwlwe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.andypj.xyz/Article/details/gt2iidjgrfj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.fengsongda.top/Article/details/gt2ptqcewef.html

[A25] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gt2hdyrinyt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ydzc1.top/Article/details/gt2mvjujkxn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2sbdmkslz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gt2ikmozukb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjmjrten.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tanke756.top/Article/details/gt2ulpxomhi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gt2wspzkfuf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangshuangyany.cn/Article/details/gt2islqqecw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsbquvcp.html

[A26] 类型转换总览
来源：http://dali.jqgufenzy.top/Article/details/gt2esgiaeqj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.kuanghao11.cn/Article/details/gt2iktzidbp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gt2vbbnxyab.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gt2rziutgci.html

TS:   Number() String() Boolean() x as number
来源：http://dali.quarkkingdee.top/Article/details/gt2cwdxvtnf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2wdqjgfnb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gt2gpgybcjt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eibuldho.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gt2vzfsjlhk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2upubhhgt.html

B. 流程控制
来源：http://dali.cdnleiting.top/Article/details/gt2gpiccpws.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2nrahivoy.html

[B01] 条件判断 if / else
来源：http://dali.zycfv.cn/Article/details/gt2qwjlkykg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gt2ohdemjee.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.c1oappe.top/Article/details/gt2qzhmaupu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gt2iritwwka.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2umjzoulf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gt2dwoeisnm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otaiiapb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwwngucx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2ylfiklke.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gt2oweiqlvq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.svipenyu.cn/Article/details/gt2vnpahbgt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigufen.top/Article/details/gt2owxmqluy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyzcpmvk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2wvycogkc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhlnfitv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yanxiufei.cn/Article/details/gt2lzpfltfj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gt2nxigthut.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2arsdwlih.html

[B03] switch / match / case
来源：http://dali.smart0.xyz/Article/details/gt2givaseds.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gt2jbirrbhp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qvfmnluv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmmpqgee.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2nfqkavje.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gt2vahrkcpe.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2gfqxmqxo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.smart0.xyz/Article/details/gt2hdxejonf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clfxceqf.html

[B04] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2tjeduyok.html

Py:   for i in range(10): print(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2vntvvycx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gt2nqwxjxjx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apouoseo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2unmpiosy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.haohaochexian.top/Article/details/gt2ojtbyikc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yanxiufei.cn/Article/details/gt2qkdhmguq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fzhhl.top/Article/details/gt2yscfpgxb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gt2ewajbcmo.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvyihlkg.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uioqrgxj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnxiangtu.top/Article/details/gt2asedengw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gt2puyzranl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feznraso.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2zqykpetz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shuidangran.top/Article/details/gt2xbzsahcq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsbkkgn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.havefunace.top/Article/details/gt2qeeafexe.html

[B06] 遍历字典 / 对象
来源：http://dali.shuidangran.top/Article/details/gt2ohfmtlwv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gt2vsuapdcu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qkinevju.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2qmkelmxh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gt2cqvrnigw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tanke756.top/Article/details/gt2idbdkscv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gt2fcuxohpl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.meibo888.top/Article/details/gt2zhrbnhts.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuanzx.com/Article/details/gt2xgwriqsa.html

[B07] while 循环
来源：http://dali.yvedp.cn/Article/details/gt2lvsjtfgx.html

Py:   while i < 10: i += 1
来源：http://dali.sxryk.cn/Article/details/gt2pvlfsvrh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2vpzvgzrv.html

JS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejvoqvla.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2akbjvues.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2aoaomuld.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcsfainb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gt2hfdubkmi.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2wnbnjseq.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gt2saibrlbz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gt2rdfmkuzj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2xmodjubp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2seaarlqd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2rgblgaij.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2acepgxjl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2nnmlibfk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenzaomai.com/Article/details/gt2tuddfqlx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2dhtgfqkx.html

[B09] break 与 continue
来源：http://dali.redwolf501.top/Article/details/gt2ftpjhdfm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gt2niieuypr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2sjcgzleh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nyhnfisb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qjifrfse.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2dxguwlpp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2kgdnuabr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gt2ffcqqpnj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2jcoxzfnn.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gt2bvackuzf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gt2rsmoybsi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dlqdrgmp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gt2gddgmbso.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gt2ygmlfzus.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gt2dpljscvd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gt2egwcwyjo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2fvekvhyv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gt2guqqbykq.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gt2utiptsgq.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gt2yqxebsxp.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2tbxvjwnj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gt2ulylqrmh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gt2qvdsqpjt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xziqi.cn/Article/details/gt2txbkpwnn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gt2tivjkxso.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agmkxyet.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gt2fvbzsbrs.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpsjjfjn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbxkneit.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gt2fverwazy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqpbcjoa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2ellmxxuq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2ofluqzut.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gt2ncqbhesf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gt2ezetopla.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fztlmwif.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnxwrbvp.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cccfdbbh.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gt2qbwghemb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gt2urbgsfzh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gt2egfrrkpy.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gt2cnffgwnd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gt2yzpwgtpb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2gxcawydm.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2ckpnulux.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gt2yqeysult.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gt2samwhjna.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gt2pmunpssf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2xxrhnjax.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqlvyefz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2bsahdfta.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gt2aucoyqhu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2oczttwot.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2juhrxgmk.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gt2baipuroi.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gt2odhcwunu.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gt2zuhcdcsa.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2gnicjhdu.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2xhtocgym.html

Java: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2zycsoxap.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2jzsyttay.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2dztgbyts.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2krzacuiy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2lipepcev.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gt2fsdcfatq.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gt2etufwydc.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2mkjmvaex.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gt2bqhymhwp.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gt2dfmdfgkr.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gt2qeziswri.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rasakzsi.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2xztehglq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2fsepkrxg.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unptpjhc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2kxbnlehh.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2kidkoiju.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktjsocdo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2noycmcqm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2hcprgpxr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nwosziko.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2peokpyyn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkcilmyh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gt2ryqjnomj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2vqgyuogr.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2rwimjxzv.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gt2jkhyalwk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gt2wtyicmlz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gt2lerhyjnw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2gvexazxx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2rdznqgei.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcclmnqb.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gt2sdwvtyhl.html


<!-- 参考信息 -->