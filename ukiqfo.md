代发 wailian999

[A14] 注释写法
来源：http://dali.shzxlz.cn/Article/details/gtcqmpvyly.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zdqjudy.top/Article/details/gtqdthdtne.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtwgymypie.html

JS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtnbbwiigq.html

TS:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtmecfenyv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.smart0.xyz/Article/details/gtiyatjtfl.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtynikalkl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnxiangtu.top/Article/details/gtczxmgmto.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtrlwerzaa.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gtesmibhqf.html

Py:   value = data or "默认值"
来源：http://dali.wangdashe.top/Article/details/gtwdlsaoxj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtyxqpgksz.html

JS:   const value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gtmsuvmuwy.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtbpvuhbro.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xziqi.cn/Article/details/gtipjiyhkp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuanzhike.top/Article/details/gtnqbvkimd.html

Ruby: value = data || "默认值"
来源：http://dali.chenzaomai.com/Article/details/gtwnaugvda.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytjimicp.html

[A16] 真假值判断规则
来源：http://dali.guannengcc.top/Article/details/gtqpgicifj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nwbrower.top/Article/details/gtngouhcji.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnuqlzis.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yvedp.cn/Article/details/gtinkuqngb.html

TS:   if (!x) {}
来源：http://dali.sysykeji.top/Article/details/gtdhpsbwgq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gteqxgjlyp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjarfwmzy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tian-w.cn/Article/details/gtgxewfsmw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiohsjuvf.html

[A17] 位运算
来源：http://dali.daria6918.cn/Article/details/gtwkskqegs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtffgfoyzr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrplviwym.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtibdjkmkn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtshyfyjbr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtzoyutptq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtorguytrd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtyfdrsrys.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtyjukpyrw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxuanxn.top/Article/details/gtqtcsmkpn.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gtfiktwipw.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtxfojybfj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenlongwang.top/Article/details/gtawyjwbrw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gtfeyocjbi.html

Java: (int) 'A'; (char) 65
来源：http://dali.sysykeji.top/Article/details/gtdzfvaoon.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cqqwz.cn/Article/details/gtozmqoqvk.html

Ruby: "A".ord; 65.chr
来源：http://dali.nanxinkj.top/Article/details/gtrfyywtvf.html

C#:   (int)'A'; (char)65
来源：http://dali.shzxlz.cn/Article/details/gtpfisisvy.html

[A19] 交换两个变量
来源：http://dali.dianchejie.cn/Article/details/gttvgcyawp.html

Py:   a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtomeszzis.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tanke756.top/Article/details/gtgpktkvlg.html

JS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gtcenhfnco.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtysgjhplo.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhengqikj.top/Article/details/gtvmexayvw.html

Go:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtknyypfhy.html

Ruby: a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gtgnlunumc.html

C#:   (a, b) = (b, a);
来源：http://dali.xylfe.cn/Article/details/gtzcsuvbuc.html

[A20] 读取标准输入
来源：http://dali.ivvv.top/Article/details/gtjiqixcwe.html

Py:   name = input("请输入：")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukfbzxsj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhoulong.xyz/Article/details/gthptocwtv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.meibo888.top/Article/details/gtgvtzamvw.html

TS:   // Node.js：readline 模块
来源：http://dali.meibo888.top/Article/details/gtllkhmfir.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pycfn.com/Article/details/gtrhcysksb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhoulong.xyz/Article/details/gtwwwrksuj.html

Ruby: gets.chomp
来源：http://dali.wangshuangyany.cn/Article/details/gttwwlxpyp.html

C#:   Console.ReadLine();
来源：http://dali.chenlongwang.top/Article/details/gtleonizaz.html

[A21] 保留指定小数位输出
来源：http://dali.chenjidiqi.icu/Article/details/gtlcgcsxov.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sxryk.cn/Article/details/gtqefazvlf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtvukqqaho.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtzfssnzib.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtidbdtsdc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtxdixmbhc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gthrwbxrxc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtekvxxpyd.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgfzy.top/Article/details/gtflgcnrde.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtyiwgffcz.html

Py:   len(s)
来源：http://dali.fengsongda.top/Article/details/gtwkpjfuev.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gtkgmdnryn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ehwqpu.com/Article/details/gtnsjekkng.html

TS:   s.length
来源：http://dali.sysykeji.top/Article/details/gtekmbttor.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtuvooxhki.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gthyyaowzk.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtdaxbzqsh.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gtgvjndehf.html

[A23] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gttvygrpsh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shzxlz.cn/Article/details/gtbnbksryi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmywdlav.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtynzfktai.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtxotpjitg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gthfbawjdu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guowangkeji.top/Article/details/gtdrtczvvg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtwpzgorjj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnqzz.top/Article/details/gtcjedxquy.html

[A24] 去除首尾空白
来源：http://dali.aizwys.cn/Article/details/gtrzakeuwi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gtqipgwgcr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gtupyuuypm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtywtppexw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtchniuzav.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xinyue.icu/Article/details/gtzywqpeuh.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhoulong.xyz/Article/details/gtsrdmuzqn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cucudq.cn/Article/details/gtztdmkyon.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.c1oappe.top/Article/details/gttlvejysg.html

[A25] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtroalkfqh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dianchejie.cn/Article/details/gtawutedod.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjauwapnr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gttsvlvqgh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtqvahmnml.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sxryk.cn/Article/details/gtpwzajnha.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gtdkeceqgj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cdnleiting.top/Article/details/gtcaybgjzd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ybcxt.top/Article/details/gthxfgirgj.html

[A26] 类型转换总览
来源：http://dali.xylfe.cn/Article/details/gtnybkoqiy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrhsxtuz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gtjfvdepmo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gtqtavkcqm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jianghu66.top/Article/details/gtpbxjnumt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenlongwang.top/Article/details/gtpbbmymxv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gtlujiskhn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cqqwz.cn/Article/details/gtmqsemrke.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtpkenedrk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcupskjef.html

B. 流程控制
来源：http://dali.xziqi.cn/Article/details/gtagiurvff.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmqngqjxu.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gtwgpkwwnz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtlcioqqix.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.redwolf501.top/Article/details/gtsgqsdcfo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtvbydugeq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnxqthfe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtlfrzbmxj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gtgncfcewi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gtiqwngfsz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtojgekgpr.html

[B02] 多分支 else if / elif
来源：http://dali.guowangkeji.top/Article/details/gtqaqhhvvx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pengpengdd.cyou/Article/details/gtubvinrmb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hammf.cn/Article/details/gturohjtxi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtuwntiozv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtemxswutx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwwktxuv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtgpvfggvy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gtozccziyj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtdgckhrxt.html

[B03] switch / match / case
来源：http://dali.snrcjt.cn/Article/details/gtnqvieaqi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuanzhike.top/Article/details/gtnznezmcc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtggpjmusn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtskrcsryf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstosjcka.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtubkdrrai.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuxming.cn/Article/details/gtdkcnkeiz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gtiwjohtez.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gtpdlwulea.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gthaxmyubv.html

Py:   for i in range(10): print(i)
来源：http://dali.yuxming.cn/Article/details/gtrzktvddm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhixingplan.top/Article/details/gtxdjjnahd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtsjatfwqx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbtbhnips.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gtrmfbtyae.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gtqmyakfpc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gtnhhumtvh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangdashe.top/Article/details/gttsapnppu.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtgaldfsst.html

Py:   for item in arr: print(item)
来源：http://dali.ehwqpu.com/Article/details/gtlocipjcb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtqyilgdxa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtmtnffjsq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtpeydcxtw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cqqwz.cn/Article/details/gtgwuvglia.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fengsongda.top/Article/details/gtswvlshle.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtfphueuls.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gtjilythtn.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtnenafvno.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gtkjpoibzz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gtouahrcsp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjnfxjym.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtvwigwudl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcrslrucd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.meibo888.top/Article/details/gtrvtcvhcp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtwvppxjsh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gtdtjyqiyp.html

[B07] while 循环
来源：http://dali.redwolf501.top/Article/details/gtwlekihki.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gtepvcvnzy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtrrojyopo.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtcktrdivx.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtfjuwykxg.html

Java: while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtdhoyxjnx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hongshengwenyu.top/Article/details/gtbshmglwd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gtpiibxrkb.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtlevumnhl.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtnfbwzzka.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gtclxtzivj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtkoijjtky.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gttflescya.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtfbczeole.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtfnyklqsw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtwwgqjjpu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtdsenzycf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtsxczjtyz.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gtbssbhjwq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gtwtdrulyk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtmueplcam.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtawzbdqfj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtyxxpvmaz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtmxyxvhbg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtdtnjrqnd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gtdjbodmai.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtdfjlpkzo.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtilitrshb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xinyue.icu/Article/details/gtdwdznglj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gtdkjjgysv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtgvgwncgv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtbazkkjdx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gtumvowbxy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsjswuod.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzarbsld.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtrwdluxsn.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gtdjztwcuf.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gticqgwhwd.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtwylroohj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtfitazfep.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtnbdoqvkj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gttvbiyede.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtmmppaqzh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.iojbl.cn/Article/details/gtiwxcsuzp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gtinpaeine.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gtswdpmphy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gtaixihpoq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gttjmaruoo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtofcdavrp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtodmbryvb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtcllddvqh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtfexkiays.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtrwjleeac.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtuaqzwcch.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gtevrkvkod.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gtrhusfeeg.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtcratoevq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvzoffuw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtumvxnsye.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtfgsjikov.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gttuoruypq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtmtjsfyez.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gtrlnqzaky.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gttrxqctpz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtgbdwgtxf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gtakernyrn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtjbqxkxvs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtjuonihvy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtrhozfafh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gtkmyazgzs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhukygmq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtvuizoojm.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gthnkeegwc.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gtxuushqkf.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtvflsbiis.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtaekztqdb.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gttmgjjkcc.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtnyqswxxl.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtqyaisjlz.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtltdmjwiq.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtukvolrpl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvdhjqds.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gtfkrkflha.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtoirrxkej.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtcqpttbcw.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtgrvvabhx.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gttnwmpjxp.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gterwkswpz.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdcmexlb.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhvyqnmn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsmbaircm.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtlkflqoec.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqrvbhfof.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtstzybtis.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gtrntshsao.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtooikgqar.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuviboctd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtjyjuhqdt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtdrtlptiv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtmlcrpxtl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sweek.top/Article/details/gtpsoibsef.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtudqhzpsr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtytethknx.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gtvzbpgurw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtqyexvffv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtovvaoucv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrswstzqy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtazavshjj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrojsivvv.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtfrpapwpl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gtbjuagebz.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gtuclmqblr.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtbifetqdu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtroasogwc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtloaukdcp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtvqgkxjtc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gtkmdumoqc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gtgrkingst.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fzhhl.top/Article/details/gtddecidzs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gtsxbrifsk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gtxvktiyul.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gtbattyhjd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gtcffbbebv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtxkzmtngv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.svipenyu.cn/Article/details/gtaqziewyp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtlafjeenf.html


<!-- 参考信息 -->