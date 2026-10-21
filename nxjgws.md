代发 wailian999

[A14] 注释写法
来源：http://dali.gzhubu.top/Article/details/gtxgncnwhk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cucudq.cn/Article/details/gtltfhdchj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gtjakilmsx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtfuppyghi.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gttpuueoih.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhongyouzk.top/Article/details/gtimkfgwae.html

Go:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtxonpxiei.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnjckqao.html

C#:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtncllwlhk.html

[A15] 空值判断与默认值
来源：http://dali.xziqi.cn/Article/details/gtolqgiuyj.html

Py:   value = data or "默认值"
来源：http://dali.yj202588.top/Article/details/gtdzsukbqr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtsruxrhnl.html

JS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtwzhnpswe.html

TS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbzqexex.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.9152youxi.cn/Article/details/gtgsqnoqei.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnxiangtu.top/Article/details/gtvzbzpmls.html

Ruby: value = data || "默认值"
来源：http://dali.gotoacloud.top/Article/details/gtigaibvol.html

C#:   var value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtvcextzje.html

[A16] 真假值判断规则
来源：http://dali.shangyingyoupin.top/Article/details/gtdmcyilsx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xziqi.cn/Article/details/gtddqebvar.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yvedp.cn/Article/details/gtjejttmxr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yvedp.cn/Article/details/gthfwunert.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhdgvfls.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxinkj.top/Article/details/gthbwifufy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhengqikj.top/Article/details/gtsvjfahyz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuxming.cn/Article/details/gthptjxmpu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ivvv.top/Article/details/gtnbskbctm.html

[A17] 位运算
来源：http://dali.fzhhl.top/Article/details/gtgasvmahw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtibsxergf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuanzx.com/Article/details/gthjjzilyf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtwthwertk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtstuzsthm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtgiwmgjiv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtzzwwgerv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtjyzkjkzq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtclgyqtuu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guannengcc.top/Article/details/gtrhggblwo.html

Py:   ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtntzzdyeq.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gtzyfoyzxw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gtzqsclpze.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtpcudgctx.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gtuscjeukm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.mhx1999.top/Article/details/gthujaukgm.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtlcieylqc.html

C#:   (int)'A'; (char)65
来源：http://dali.cashguo.top/Article/details/gtgowzrnba.html

[A19] 交换两个变量
来源：http://dali.nanxuanxn.top/Article/details/gtepewxtuc.html

Py:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtvbrsotmv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.c1oappe.top/Article/details/gtgrlbrcqo.html

JS:   [a, b] = [b, a];
来源：http://dali.cqqwz.cn/Article/details/gtdeausuid.html

TS:   [a, b] = [b, a];
来源：http://dali.chenlongwang.top/Article/details/gtqtbsspip.html

Java: int t = a; a = b; b = t;
来源：http://dali.tian-w.cn/Article/details/gtnfileioh.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtyezykvcu.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtorepkwam.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gtmuelvilb.html

[A20] 读取标准输入
来源：http://dali.yanxiufei.cn/Article/details/gtjobrvbkm.html

Py:   name = input("请输入：")
来源：http://dali.iojbl.cn/Article/details/gteqqeodct.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xinyue.icu/Article/details/gtkqmguloz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.svipenyu.cn/Article/details/gtwrztcgiv.html

TS:   // Node.js：readline 模块
来源：http://dali.bjfxy.top/Article/details/gthmqmpdoi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ivvv.top/Article/details/gtntswmkwm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xylfe.cn/Article/details/gtgmvkxbog.html

Ruby: gets.chomp
来源：http://dali.daxiang520.top/Article/details/gtwnjgeqwq.html

C#:   Console.ReadLine();
来源：http://dali.mhx1999.top/Article/details/gtqjfwsxnl.html

[A21] 保留指定小数位输出
来源：http://dali.bjfxy.top/Article/details/gtbpnqbxgz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhixingplan.top/Article/details/gtymgufjei.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtehwvvsss.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtuaohaxgg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtcnpvzklx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtspkvxmkg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtcfehcusg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtfjqtfbfa.html

C#:   3.14159.ToString("F2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatagqkhg.html

[A22] 获取字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtcjhrzyvm.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtmdrflfzn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.0kj1m.cn/Article/details/gtrsbhuwis.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gogol.net.cn/Article/details/gtbkizqryd.html

TS:   s.length
来源：http://dali.yvedp.cn/Article/details/gtlzwlpesq.html

Java: s.length()
来源：http://dali.nwbrower.top/Article/details/gtzeluxvmm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtakheydlo.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gtbfdgafnq.html

C#:   s.Length
来源：http://dali.xuanzx.com/Article/details/gtoentaelh.html

[A23] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtaivygymh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtcduwvwwk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtaenybyes.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnydmzrxe.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gtfvpcmrzf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtquemvyeq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xinyue.icu/Article/details/gtgrjazvcb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtoxqpihlu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tanke756.top/Article/details/gthymbhane.html

[A24] 去除首尾空白
来源：http://dali.tianlin.xyz/Article/details/gthhfwmtzh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipglwjhp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.snrcjt.cn/Article/details/gtackreutv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtsdvtynwi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gtxphvgtow.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sxryk.cn/Article/details/gtlcsazzzs.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gtxojjzuvm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuanzx.com/Article/details/gtcaaorehs.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tian-w.cn/Article/details/gttrcaaars.html

[A25] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtpfkzrgqx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.quarkkingdee.top/Article/details/gtswidtcfv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ehwqpu.com/Article/details/gtkyabcekx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gtsnrovjfx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdqnwomc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.snrcjt.cn/Article/details/gtmcrijwst.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtjrpdijhc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gtnsqwxpem.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gtwyoozwoj.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gthrolgdoj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gtucmygjop.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuanzx.com/Article/details/gtrohubosb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sxryk.cn/Article/details/gtueuaxsvi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zycfv.cn/Article/details/gtlvzfierj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtbcwmlraz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtnwtoipio.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkieyddoq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gttfknexsg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtspwhasep.html

B. 流程控制
来源：http://dali.wangshuangyany.cn/Article/details/gtesvknvry.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsyauwmbg.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gtpoksknei.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gtokimhlaj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yongpay.top/Article/details/gtdossimeu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtmxuascin.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtgrkestfl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtiobdsich.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgufenzy.top/Article/details/gtxyvfudmj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.snrcjt.cn/Article/details/gtpdtpgetz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtootnbuao.html

[B02] 多分支 else if / elif
来源：http://dali.hysaishi.cn/Article/details/gtmoyennsx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.c1oappe.top/Article/details/gtcmroteqq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yueranfly.top/Article/details/gtzrazcncp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtqmubbwdg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtxjvunjyb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtwncupceg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yanxiufei.cn/Article/details/gtzggeevsu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gaohongyu789.top/Article/details/gtlgeceqga.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtgmomuovd.html

[B03] switch / match / case
来源：http://dali.jinqigufen.top/Article/details/gtafxerxbd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tianlin.xyz/Article/details/gtgjajiaml.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthbwctlz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtkgymwndn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gthihbdfzk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtkrbfkhug.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhltlzgz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gtbxitimog.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pycfn.com/Article/details/gtjtwjnqao.html

[B04] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqhmkibf.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gtddmysnfh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gtoivfggup.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtxhrvrnfs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gtcuvfpmfw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yvedp.cn/Article/details/gtwqatlypb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjrxbaie.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gtfmsvpjsd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gtcarxpccf.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtohvpnsvc.html

Py:   for item in arr: print(item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaognjbh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnxiangtu.top/Article/details/gtzbvjmdbs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyxhoqpv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtxxyrqwlz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtddmpzxfe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ehwqpu.com/Article/details/gtnvqlocxw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtrpdyeird.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sysykeji.top/Article/details/gtrmlycymj.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gtigczhvso.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenzaomai.com/Article/details/gtalrhjntp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gtekgutmwv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtaalazuwb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuczzkgnd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jlsjyb.cn/Article/details/gtsulqzejo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxodlfkn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtgbkczrew.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtbdepioep.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gtdnzhmmlg.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtbkrqhfdm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gtzdgcmldb.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtecqlviol.html

TS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtqsavxfmc.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcxijhtnj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtxeaqfsxl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtdencfole.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtksytdqzr.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxinkj.top/Article/details/gtudzwgpqj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtvtgegluu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtgcatwjab.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtdqkhrzdj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtqzmeejqz.html

Java: do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtfsufldet.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtybwnfffw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gtqqutkzwp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtvlpnhcxf.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtgqjtyggg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhengqikj.top/Article/details/gtoxmlfxvv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoghakgzq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtfkymuxzn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtondqpwgy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtangpkxse.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gtpedmilhl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gthiagbhwm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwtlroivg.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtkstrzuxj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ppjwa.cn/Article/details/gtecshktcm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsptugui.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtaxabfpok.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gtvxvtmfpb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpjkqnxnx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.feifeiyinyue.top/Article/details/gtbrrvobqy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gthwpyopul.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuanzhike.top/Article/details/gtfnsxwkig.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gthckrxmsd.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gtvxobvjoc.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gtdwhpyssd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtwoomnrlo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtsboapiok.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtninctptc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtgljlymjp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtqowkfqmw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtzoyidmqj.html

[B12] 跳出多层循环
来源：http://dali.guowangkeji.top/Article/details/gttkshrihz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtjyinqgjf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtdlqbebnl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gttgjcidbi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtwawflgll.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiboixaj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtiuyjjwec.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gttdowzpbr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gtrrpknfbl.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwkaeafq.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gthvbxvprj.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtxknimufw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtcxhldtur.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtyfpqprdt.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gtcdnuzrhy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guowangkeji.top/Article/details/gteyyceiqs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gtcqeauzap.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gtxexckrrx.html

[B14] 判断值是否在集合内
来源：http://dali.pengpengdd.cyou/Article/details/gtzrgvldqa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoipuesrm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtszhqgneh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtkgqgsimj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtcqmpmxmz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gtapfgzwky.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gtwojpceic.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtzcszkxqo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqkivsdsr.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gtviyrccmm.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gtxcafrakj.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gthydubrsz.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqnxfsfe.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtxddnaxwd.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtmaikpcee.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehuzedly.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtfycldtle.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtxnwhiixs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdjshlel.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gtavnpmmal.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gtdfhcemxd.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtjlbwvlvc.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtjrgzqdza.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtrxaywksz.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtyjowktjy.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtkpnneuew.html

C#:   if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gthmkebudp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwhuviwgo.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gtppbwpgnb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtoacjbrlh.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtvqxmxviq.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gtmnwiowmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtjoxihsts.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtvmmzxbys.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gthkxlmwlo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgwxgscf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtydhmdudo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtkxejscvw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtnonalsbv.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtvukckjda.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gtpnjetqlo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtmkyppzha.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtekcsffdi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtvqwbrkin.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gthhloadht.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gtdehjrusy.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gturnwwpca.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtngcfxydp.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtnaegpsyi.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtqrwywsca.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtkmnxvlsu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtejrnpwef.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtivhtpujz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpzroirls.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xinyue.icu/Article/details/gtmxgtpyqo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuyaausz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtzbzxitmt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gthtiljbop.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtnemtcyoc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtoekznszj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszpxdnxw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtbchoqrov.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtahayypeu.html


<!-- 参考信息 -->