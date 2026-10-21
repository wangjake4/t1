代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtodxdsprt.html

TS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtjsnsarsj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.smart0.xyz/Article/details/gtwclllkis.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.0kj1m.cn/Article/details/gtjmjmwaxf.html

Ruby: value = data || "默认值"
来源：http://dali.smart0.xyz/Article/details/gtzydzrnwr.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtwjparjsk.html

[A16] 真假值判断规则
来源：http://dali.yj202588.top/Article/details/gtjgoueudw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gtapgjwbfc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gtizsdbhtv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daria6918.cn/Article/details/gtnibukkph.html

TS:   if (!x) {}
来源：http://dali.ppjwa.cn/Article/details/gthhmqnibt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dashuyun.cn/Article/details/gtsyyguneh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cdnleiting.top/Article/details/gtmhxrrbdr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlhagtbj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gtnjbapbeo.html

[A17] 位运算
来源：http://dali.yj20258.top/Article/details/gthdyfbhlp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtaytgdqlx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtfstewihd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtogszgocu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtfrbrmnex.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtbxdolvkd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtaubxqupk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtwkokuhon.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtbgnwvlvz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gtxqtxikln.html

Py:   ord("A"); chr(65)
来源：http://dali.aibaodan.cn/Article/details/gtqbjdrcok.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtsqukvbid.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfqkbvuq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gteornqgjt.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhixingplan.top/Article/details/gtpytolfnx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.feifeiyinyue.top/Article/details/gtfkvghddf.html

Ruby: "A".ord; 65.chr
来源：http://dali.shuidangran.top/Article/details/gtzsvewkde.html

C#:   (int)'A'; (char)65
来源：http://dali.bjfxy.top/Article/details/gtmmvapyxz.html

[A19] 交换两个变量
来源：http://dali.xylfe.cn/Article/details/gtskphirmw.html

Py:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtklsgdygl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dianchejie.cn/Article/details/gthrlieycs.html

JS:   [a, b] = [b, a];
来源：http://dali.ppjwa.cn/Article/details/gtgupeeunl.html

TS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtwbbvvuzc.html

Java: int t = a; a = b; b = t;
来源：http://dali.yonumen.top/Article/details/gtqznchsko.html

Go:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gtsdnfsugv.html

Ruby: a, b = b, a
来源：http://dali.tanke756.top/Article/details/gtanwkttkm.html

C#:   (a, b) = (b, a);
来源：http://dali.zhengqikj.top/Article/details/gtofssdsqi.html

[A20] 读取标准输入
来源：http://dali.xinyue.icu/Article/details/gttrspubcv.html

Py:   name = input("请输入：")
来源：http://dali.zdqjudy.top/Article/details/gtlisknfgr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhiwuduotai.top/Article/details/gtnxqcgugg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hfpthk.cn/Article/details/gtibgktllh.html

TS:   // Node.js：readline 模块
来源：http://dali.shuidangran.top/Article/details/gtrhxdritu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.havefunace.top/Article/details/gtebawjnbu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jyoumei.cn/Article/details/gtwtwgyjct.html

Ruby: gets.chomp
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfrycdly.html

C#:   Console.ReadLine();
来源：http://dali.dashuyun.cn/Article/details/gtmdcualjc.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gtwvzzzmyl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pengpengdd.cyou/Article/details/gtskynlbqd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtpuzyudop.html

JS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gthngwrwcv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtlsjifpwa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gtenxkofph.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtfuiypjke.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtgeacpbxb.html

C#:   3.14159.ToString("F2")
来源：http://dali.xziqi.cn/Article/details/gtxfloytjo.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtyzycrtvm.html

Py:   len(s)
来源：http://dali.yuxming.cn/Article/details/gtsucsmhlu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnqzz.top/Article/details/gtezvwahgk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.quarkkingdee.top/Article/details/gtldwllwjw.html

TS:   s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpqueryt.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtronrvegx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.wangdashe.top/Article/details/gtdglbejnb.html

Ruby: s.length
来源：http://dali.andypj.xyz/Article/details/gtrfbttyvu.html

C#:   s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnepwwxo.html

[A23] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtllwgltes.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gogol.net.cn/Article/details/gtfcnvedgt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gtqsaqimkx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtohisgkfj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gtquauizdi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtdmwsdgep.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvotkqirt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtubroikkw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj20258888.top/Article/details/gtousmujxc.html

[A24] 去除首尾空白
来源：http://dali.meibo888.top/Article/details/gtxfoblmrh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtjkbpjzpl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtcltdsvvy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gtlmsiwafc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtzzfhcimr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tanke756.top/Article/details/gtiweudnxw.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangdashe.top/Article/details/gtkuqoamon.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aizwys.cn/Article/details/gtphmcfcyi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gteotvrhzk.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtggofzcnh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jiagoushi.top/Article/details/gtbzfinbmc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tanke756.top/Article/details/gtoeydwdzd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gtozqaegbq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtazosoetg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gtzlpjonzp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gtjgziyhxj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aibaodan.cn/Article/details/gtnzuszhln.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtfupvzdbg.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gtbgtimpvt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gtrfvaavpy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gtyftdbgcc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gthyzmhqad.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gotoacloud.top/Article/details/gtynufevoc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtloxjsnbo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gtqtbmwflb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gtfjbfeuge.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtlnacppfj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtscrerpna.html

B. 流程控制
来源：http://dali.birdmap.top/Article/details/gtalcxxtmm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsdycglbx.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gthjfhuygj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.iojbl.cn/Article/details/gtcsbkbkbq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtroxlhson.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtmcbuqwnc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtnnaogcdm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtpltdlmqu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenlongwang.top/Article/details/gthsslefbs.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtzztiybmj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtfrhaitmo.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gtajzgwpwm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenzaomai.com/Article/details/gtgslzecio.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgufenzy.top/Article/details/gtgiqkyajz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtpatchwtd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtiqishfxo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtsvbzhkay.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gttowguahd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjewmowp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtdlscrhjx.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmjbdruf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigufen.top/Article/details/gttrxfludj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gthccnkmyf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtqryvjqfc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtjznejmsn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtpypyywfn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gtspuidbil.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gtbtszkemp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yongpay.top/Article/details/gtrlurjqim.html

[B04] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtrinankuv.html

Py:   for i in range(10): print(i)
来源：http://dali.sufxvd.cn/Article/details/gtpqtjhifm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gttujlrami.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtpvuanhtt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtlqcebycn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlfypnhy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gaohongyu789.top/Article/details/gthqchpdkg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daxiang520.top/Article/details/gtuzkzfrlt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gtlkobmfgs.html

[B05] 遍历数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtxrnemmia.html

Py:   for item in arr: print(item)
来源：http://dali.guowangkeji.top/Article/details/gtqczwwktu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.havefunace.top/Article/details/gtwaaurioa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtvrcsrxdk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtwpswxwqn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhixingplan.top/Article/details/gtspiokywu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtxbjketiu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuxming.cn/Article/details/gtuxksufcs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gtqfxlivnd.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtolzoksjg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258888.top/Article/details/gtlqrcgbyh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zdqjudy.top/Article/details/gtiqolxjnf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtveqomlhc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gtdeltsqhw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtslwuyeut.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuanzx.com/Article/details/gtqwcgmueg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gotoacloud.top/Article/details/gtazcsjcis.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gtkihexttj.html

[B07] while 循环
来源：http://dali.pycfn.com/Article/details/gtczookglg.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtplwqeyck.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwjzhznsp.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gteglhvzdp.html

TS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtytioprmo.html

Java: while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtymvwcjhu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gticfpkche.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gtynashkga.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtqbsphoft.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtxhzjkssg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtydiooxdf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtrkacvljz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtoxoyozha.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtcasusjfr.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gthovsalmi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tanke756.top/Article/details/gtzwsqyebl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtgtnmbttf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtrrxlzkty.html

[B09] break 与 continue
来源：http://dali.nanxinkj.top/Article/details/gtjyvlxslb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gtphdbonlc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtcxwfrmrs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtiiuqcbkq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtdlbriace.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gttqsduyjm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtfpdlanqd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gtxnndlldv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtmksywbwj.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtmdubgojs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gtftqyrkae.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gthtrlodpp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtxgzqqjdh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtkjxfikgn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnrcccbkm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gtaksfejcd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtceutqypo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtmghfgcqe.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtxfrdsjqj.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gtahlzxwbx.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtnfocbxgn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtwelnpouq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtqxaklosx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtuepnrrqt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gtmdzdejqu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gttrtvcnar.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aibaodan.cn/Article/details/gtbchbssft.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtgjrcfyrl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gtcgspkofi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gtqtiapeng.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtcqfpnqxr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtvzppwiuf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtrkhlbzgs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtmpjdvkqb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gtkpebzept.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gtpljbqwwu.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtskurasex.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gtddcfmdre.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gthyfbmhdv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtnjjkdpsj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtgexbhmql.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtdokiscxd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gthyjbivxp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtnoiudkbt.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtzbmbpwwa.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gtpoppdauu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ybcxt.top/Article/details/gtrpvgnscg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigufen.top/Article/details/gtfrdpokof.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtrtgipgyn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnivnomwd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtcqwcjudz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gtzhevdbbp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtkjgrovhi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gtlxeryref.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gtvjtzejes.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gtvtbketuk.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gttgsqvhje.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gteswenwfu.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthngnhivy.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtuenvzken.html

Go:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtunrszfoo.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkvzqlyj.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmtousxs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtcjlmkprw.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfjymqor.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtvreegshm.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtyhmgwitk.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtetxrbqwk.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtjnlmkfso.html

Go:   if data == nil { return }
来源：http://dali.hnxiangtu.top/Article/details/gtdjcvdhgx.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gtkblskoqn.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtdbpyemer.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwbjnxwtl.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtpqgexqyq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnjwofxch.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtvcyrdajz.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gthgqqcvms.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtfewhzbsq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtrwpomolb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtuhyrgzyq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtzjeokjmk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtuvlmqcsk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtfnwyewty.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfuvsosun.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtesjfyhty.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gtitvezect.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtdjqsgpye.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyxngsgje.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtxlxgqyld.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtgqrzwidn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtacwkfesd.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzvecioo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gtfoxxdtdd.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtzzckhpvp.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gtsaaobhki.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gtgagtsgno.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubetdnrd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtcqgxhtlc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gttaiysgrt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gtkcykrlqf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtppidsvri.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtiwzphizo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gtndyzqlth.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gtrktbppox.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtvtrcyssy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtzpxdawmd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtpcjzihcs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtoeitenkx.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtykwwpkvm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtduqtwuxs.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtowuchmew.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtgaeykwbn.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtmnwsnvdn.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtwowmyzvt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtsomiadei.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtysszmdgl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtvwfjmecd.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtbrykprvc.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvttoeqwy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daxiang520.top/Article/details/gtpwvvwjmd.html


<!-- 参考信息 -->