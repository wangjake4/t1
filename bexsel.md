代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtnyvrxmqt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtgvlkflpc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhoulong.xyz/Article/details/gtfosdhpwx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.quarkkingdee.top/Article/details/gtdwhythns.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnemoaco.html

JS:   `Hello, ${name}!`
来源：http://dali.zhiwuduotai.top/Article/details/gtbiaxqpgn.html

TS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gtyyrtxwtr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gotoacloud.top/Article/details/gtnfwsgmyp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aizwys.cn/Article/details/gthgigjqed.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuxming.cn/Article/details/gtjbxwbujp.html

C#:   $"Hello, {name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtxqghgvtw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jqgfzy.top/Article/details/gtpjehjtql.html

Py:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtrvvaxtpp.html

PHP:  "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtltoraxsw.html

JS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtlmzipums.html

TS:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtrtdxahhb.html

Java: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtbadzhvbk.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtjnhjzgdj.html

Ruby: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtpmrykkni.html

C#:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtwfpoidni.html

[A14] 注释写法
来源：http://dali.c1oappe.top/Article/details/gtuthlvvro.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.vqdsnc.cn/Article/details/gtgevcoorh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtkxswbcgc.html

JS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtftbyiwel.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtveietguj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtgepvnbtv.html

Go:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtestdxopx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbrdoihc.html

C#:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gtbipiyoqt.html

[A15] 空值判断与默认值
来源：http://dali.jinqigfzy.top/Article/details/gtiinljlza.html

Py:   value = data or "默认值"
来源：http://dali.birdmap.top/Article/details/gtxjrmynjl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gtwmsrxyhq.html

JS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtzfexucfo.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtzpvseufr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcwsgwqv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yueranfly.top/Article/details/gtvlupgaad.html

Ruby: value = data || "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyecdqqbq.html

C#:   var value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtagvbvhfu.html

[A16] 真假值判断规则
来源：http://dali.dianchejie.cn/Article/details/gttjnvkqmm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiakbwsa.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvqgsevv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhoulong.xyz/Article/details/gtlflgjnzr.html

TS:   if (!x) {}
来源：http://dali.jianghu66.top/Article/details/gtbiqedlix.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcbtmfdsr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.meibo888.top/Article/details/gtyyiqzvxg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxvqropm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtthvrsscz.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gtfaadgygf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtpbboqqty.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtdlsyhseo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyqmnabp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtkvjrzwzq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtktjeubyx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtokdqomzq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtsakbyaho.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtsxyxeumk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yanxiufei.cn/Article/details/gttjyrpfna.html

Py:   ord("A"); chr(65)
来源：http://dali.shuidangran.top/Article/details/gtuvqizwit.html

PHP:  ord("A"); chr(65)
来源：http://dali.yonumen.top/Article/details/gtnrxzwcuq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gtmmmczxja.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gtxffxxgvy.html

Java: (int) 'A'; (char) 65
来源：http://dali.mhx1999.top/Article/details/gtaaafaito.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258.top/Article/details/gttesfezsj.html

Ruby: "A".ord; 65.chr
来源：http://dali.hongshengwenyu.top/Article/details/gtperpbfwp.html

C#:   (int)'A'; (char)65
来源：http://dali.9152youxi.cn/Article/details/gtauedvycb.html

[A19] 交换两个变量
来源：http://dali.jyoumei.cn/Article/details/gtyrsmzezy.html

Py:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtazbwevxf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.smart0.xyz/Article/details/gtcqyrfiuj.html

JS:   [a, b] = [b, a];
来源：http://dali.daria6918.cn/Article/details/gtfmrapsqb.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gtnihpgblm.html

Java: int t = a; a = b; b = t;
来源：http://dali.zycfv.cn/Article/details/gtjojatrfw.html

Go:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtytwdnuzc.html

Ruby: a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gtvozdbrri.html

C#:   (a, b) = (b, a);
来源：http://dali.birdmap.top/Article/details/gthlhdxkda.html

[A20] 读取标准输入
来源：http://dali.nwbrower.top/Article/details/gtsbqxutzx.html

Py:   name = input("请输入：")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlycubgju.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gtjcnsbuqj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guannengcc.top/Article/details/gtnoywbkow.html

TS:   // Node.js：readline 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtxfpagolb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jianghu66.top/Article/details/gtryspatak.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangshuangyany.cn/Article/details/gtozfpuwzb.html

Ruby: gets.chomp
来源：http://dali.tian-w.cn/Article/details/gtkhfrckwm.html

C#:   Console.ReadLine();
来源：http://dali.guannengcc.top/Article/details/gtsecbxwyy.html

[A21] 保留指定小数位输出
来源：http://dali.yuxming.cn/Article/details/gtkncmiwla.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj202588.top/Article/details/gtzrtfheyf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtojqctrcj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtsrjmfojx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtgzezvhhi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtgwmlxbba.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtdnmjmyjr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtmmcpbvdi.html

C#:   3.14159.ToString("F2")
来源：http://dali.hongshengwenyu.top/Article/details/gtvokxsjxc.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtozducizy.html

Py:   len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtrrtwinon.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xylfe.cn/Article/details/gtfpoqezsv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jyoumei.cn/Article/details/gtijspfgig.html

TS:   s.length
来源：http://dali.gaohongyu789.top/Article/details/gtkmhumoej.html

Java: s.length()
来源：http://dali.smart0.xyz/Article/details/gtueapuxjm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.havefunace.top/Article/details/gtdxtpqotx.html

Ruby: s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtbakonshv.html

C#:   s.Length
来源：http://dali.shzxlz.cn/Article/details/gtonmjtfgp.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtuyujvjmm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.bjfxy.top/Article/details/gtekwccqcx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gtjeweaxlv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gttfhfkeba.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtsloiuews.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtsffkgaxs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxqfnwrh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwiywbzs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ppjwa.cn/Article/details/gtfyvfdlhc.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtvaowlehi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.daria6918.cn/Article/details/gtjxvkimvz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gtdunemahv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtjtbztled.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtyoermoio.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cucudq.cn/Article/details/gtfrtrlpzr.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtcptmsnpx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gthrknyjnv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtacldixmf.html

[A25] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtcpcigkac.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuanzx.com/Article/details/gtfseuvqai.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtirxcqsse.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gtquhskqmr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gtjdwiajri.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtggzsgebg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gtfaptydzc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.meibo888.top/Article/details/gtnmhglvdz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtzmuhgrec.html

[A26] 类型转换总览
来源：http://dali.tanke756.top/Article/details/gtyvgvupwf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gtrjuymqvb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gtfuzqgylp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gtfqztbyoi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.c1oappe.top/Article/details/gtcpohroyg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gtbrpxjlxx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jyoumei.cn/Article/details/gtxfzaofsr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gtzwfzgpkg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtzidnaezl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuepqmgrd.html

B. 流程控制
来源：http://dali.vqdsnc.cn/Article/details/gtxzfbnhbp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthaemyymw.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtpgppeivp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gtfnqzmkdl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.andypj.xyz/Article/details/gtlkewurud.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtyhwfjotv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtlauelwhe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtxdvpdqfv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gtlqpvznbt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gtgxmahxry.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gttapgjytq.html

[B02] 多分支 else if / elif
来源：http://dali.hongshengwenyu.top/Article/details/gtfzabfzau.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gthwqtaooa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.birdmap.top/Article/details/gthmzsimww.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtesyumoji.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gttmdfvdse.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtsfuqiicw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenjidiqi.icu/Article/details/gtzyoyyqbm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenlongwang.top/Article/details/gtclsztnfc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtsofibtru.html

[B03] switch / match / case
来源：http://dali.svipenyu.cn/Article/details/gtgyqqzcbw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gtptzbcwqj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtrjkvuxor.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gthbqgflwb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaduxegaw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtzpjpyusm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtohrrgmpn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.redwolf501.top/Article/details/gtnbngsnfm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gtfnpckmao.html

[B04] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtvomtettn.html

Py:   for i in range(10): print(i)
来源：http://dali.zhongyouzk.top/Article/details/gtijwcchlz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzeqcpegm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gthuvvnldl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtpuveyleu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.smart0.xyz/Article/details/gtnutdenhh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guowangkeji.top/Article/details/gtrthajrvb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nwbrower.top/Article/details/gtrljigxtx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gtlbilqlfu.html

[B05] 遍历数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtfiafuvum.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gtfdvqcace.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gthafjalga.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtgnofkrym.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gthexwpdfg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gtnaymekgk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jiagoushi.top/Article/details/gtjtycmcyt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xylfe.cn/Article/details/gteiveqgjo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gteupvripk.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtirzlyejx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhixingplan.top/Article/details/gtqpuhnsxq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxuanxn.top/Article/details/gtanccbfuo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gteukmzkrh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gtoonyjgvx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gtashkrgbt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gtngliztog.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuanzhike.top/Article/details/gtlnyimlia.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtzvkxdhxd.html

[B07] while 循环
来源：http://dali.hysaishi.cn/Article/details/gtjendvkes.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gtlrhuifwu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtfjuajehy.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtowomdcst.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtmbpylklw.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtackurcoy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gtczrxzjng.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gtxiornxyb.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtktkpgaso.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gtrsybjsmz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvhtcxuc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtorbpytkc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtyvwiawgd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtetfzekdm.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtqrlzwjok.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtuyiiwhfd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtfakmnive.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtwgqruwbi.html

[B09] break 与 continue
来源：http://dali.zhiwuduotai.top/Article/details/gtdjevxrfq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gtxxbmhgru.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtoyedcmrc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtovuqmnhq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtitclznnm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtlnkrgpjr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtzvoxqwns.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sweek.top/Article/details/gtmrhwxyys.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtyfmgfdkg.html

[B10] 遍历同时拿索引
来源：http://dali.cashguo.top/Article/details/gtpeuklgqk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtnfcrejar.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gtolewxwjv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxhfoszt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gtjqagfjrn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtopbllpin.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sweek.top/Article/details/gtvhgeaepr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtxbfyolrb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gtvortfmdg.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gtdnxhdvxm.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gtawscqisu.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtkhkakbre.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtkxcvrbje.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtrkzllzmd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daxiang520.top/Article/details/gtakrmivbl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtjxnlkvde.html

Ruby: (0...10).step(2).to_a
来源：http://dali.andypj.xyz/Article/details/gtrgmlyxdq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtwjhrdnyb.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gtsdmcvxdr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gtrkwtawxg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guowangkeji.top/Article/details/gtqaidffmm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtmmyagdjb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtiiyadybe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiokskir.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gthywazrjp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtotoppeyr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsewlofh.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gtnzimwfjc.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtzcaxulyg.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gthpypqygs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtkcjsdijp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtmuubnioj.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gtppzkeaiw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gtqqpeufgu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gtykskievi.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtebgrydys.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtujlprdkm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gtjgrajicq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gtouqkbwnr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukuhufem.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtjnpqdpyn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtlcglqnyb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrkfprzrn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtpffiwsuo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtuoodomsh.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtyrgrpwfq.html

Py:   a and b or not c
来源：http://dali.yvedp.cn/Article/details/gtnzvhrjog.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtygfertsv.html

JS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtkkmqlwvc.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtffxiiihr.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtvpbmiren.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtyneykuun.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtttrupgpt.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtrfduqhtp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtxspvfrcd.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtnhcgntmi.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtkyoajmvr.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtasjxkfvj.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtkyiplgrk.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gthznzztqb.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtirhfkuyc.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gtgqmgwjhj.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtawlhgeyy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxnsznswg.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gtaodiqilk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkkjxrwdr.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtmiiaptne.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtngqvnnqz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrexmsqxp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtgtqllnrf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtlvxgytaw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtiwtekydt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtrtwpizxq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzxoxihec.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gttoccggtm.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtufwvktss.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxuanxn.top/Article/details/gtuxxgzhef.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj202588.top/Article/details/gteriwrerx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtswskvulj.html


<!-- 参考信息 -->