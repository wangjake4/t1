代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtrqjvyjkq.html

TS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtfwlrltjm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jiagoushi.top/Article/details/gtziwdjfpi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj202588.top/Article/details/gtljwefkzl.html

Ruby: value = data || "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywmgqopd.html

C#:   var value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtqnrebkvv.html

[A16] 真假值判断规则
来源：http://dali.dashuyun.cn/Article/details/gtydgsjwxs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258888.top/Article/details/gthxdgrcqc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hammf.cn/Article/details/gtpnvqukzn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtnfvpbvdk.html

TS:   if (!x) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyffepzku.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cheryme.top/Article/details/gtahuuvdgm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhixingplan.top/Article/details/gthhswrmdz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tianlin.xyz/Article/details/gtbknwnakn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.iojbl.cn/Article/details/gtgcoalcey.html

[A17] 位运算
来源：http://dali.jyoumei.cn/Article/details/gtuptpbtzh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtmvlbyrlq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdmlwkwt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtgmckxqmn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtddheexfx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtmyhzxqax.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtmhsxqygq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtdeyuqpuz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdvhnhay.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cqqwz.cn/Article/details/gtqabnkjue.html

Py:   ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtgzpuiviv.html

PHP:  ord("A"); chr(65)
来源：http://dali.tianlin.xyz/Article/details/gtjxlbtkyf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gtxcfadskf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gtzucxpkjh.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxuanxn.top/Article/details/gtuwrwpnes.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hysaishi.cn/Article/details/gtjlibukgq.html

Ruby: "A".ord; 65.chr
来源：http://dali.quarkkingdee.top/Article/details/gthoxmdrbi.html

C#:   (int)'A'; (char)65
来源：http://dali.chenjidiqi.icu/Article/details/gtwvrjldfx.html

[A19] 交换两个变量
来源：http://dali.birdmap.top/Article/details/gtencgouzx.html

Py:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gtdjgjxpwm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkpkyzqo.html

JS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtbriuqtfu.html

TS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gtnujqzloi.html

Java: int t = a; a = b; b = t;
来源：http://dali.iojbl.cn/Article/details/gtbkquvrsp.html

Go:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtunusejtn.html

Ruby: a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gtpnwkedqq.html

C#:   (a, b) = (b, a);
来源：http://dali.svipenyu.cn/Article/details/gtqytutlkz.html

[A20] 读取标准输入
来源：http://dali.haohaochexian.top/Article/details/gtexqlhgtw.html

Py:   name = input("请输入：")
来源：http://dali.cqqwz.cn/Article/details/gtmhmondwt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.316326.xyz/Article/details/gtucjpkbqy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xinyue.icu/Article/details/gtlmvswcnw.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgfzy.top/Article/details/gtppuerlvy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dashuyun.cn/Article/details/gtvlrjhbop.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangdashe.top/Article/details/gtsoxseyut.html

Ruby: gets.chomp
来源：http://dali.yanxiufei.cn/Article/details/gtzsxassis.html

C#:   Console.ReadLine();
来源：http://dali.yangfankeji.com/Article/details/gtaubyqxhm.html

[A21] 保留指定小数位输出
来源：http://dali.tianlin.xyz/Article/details/gtwciesfiy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shangyingyoupin.top/Article/details/gtfxsmbzhp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtxrlrdznn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtqvqacmrq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtsykfezoo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gtibgwsjha.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtzbidxona.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtbnpeocmc.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gtzctjzxgo.html

[A22] 获取字符串长度
来源：http://dali.havefunace.top/Article/details/gtbajxfnsh.html

Py:   len(s)
来源：http://dali.fengsongda.top/Article/details/gtwqrpondw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.feifeiyinyue.top/Article/details/gtsdtrgxtu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuanzhike.top/Article/details/gtdenfwnzp.html

TS:   s.length
来源：http://dali.chenzaomai.com/Article/details/gtonjidhli.html

Java: s.length()
来源：http://dali.gotoacloud.top/Article/details/gtzbkvdjmn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtriotxxyw.html

Ruby: s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfrawjgx.html

C#:   s.Length
来源：http://dali.xylfe.cn/Article/details/gtnmadagej.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtzpragray.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtwyvypaai.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shangyingyoupin.top/Article/details/gthvnsuget.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtezrkdffv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtztrsoppm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tanke756.top/Article/details/gtcczcrzbs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.dashuyun.cn/Article/details/gtmiewxlln.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtefxtlqxf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtkhcuzrqr.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzfydqwt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shzxlz.cn/Article/details/gtcoyampjj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhengqikj.top/Article/details/gttfduyvoc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gtdygubqbk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtojxmpqfi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlulpflo.html

Go:   strings.TrimSpace(s)
来源：http://dali.hammf.cn/Article/details/gtwfhzchto.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gtssnfkrjc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yongpay.top/Article/details/gtquspxqbd.html

[A25] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtuokistwf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ydzc1.top/Article/details/gtrfkhnnfj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtjcoeejzz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gtkycttkpy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gttcnpulmx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtgrqzgfli.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gtygivmsck.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gteapnnhjl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtoltdeter.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gtoptgaakm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhengqikj.top/Article/details/gtohpncujj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexkoxpyk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhiwuduotai.top/Article/details/gtycunkgdi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ivvv.top/Article/details/gtpaznpkvr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtipoqohij.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtulqhckcd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gtsefmzoxr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtemohxvbz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzmfqqnai.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gtdwmohvpn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthoovszfs.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gthyscxodx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gtvhginwfu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gttpfcfhev.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gthelmgagt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtakmzuyhl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtngfplwfv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gtrvnyvwew.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gtrvlvpnyl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gttlwsanra.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtnmaknijr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhongyouzk.top/Article/details/gtgpazfnyi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenzaomai.com/Article/details/gttfvjjxkm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtysbcolgh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtojiebzpe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gthdiynpyb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhixingplan.top/Article/details/gtdcjffjly.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gtnvsmqvaa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtgkxatbqk.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gtkhhecfco.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gtithxftpn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtbmhexwxz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtluzxigmw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtupuddbca.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gthrfxsyhl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtmmbuhsuw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xziqi.cn/Article/details/gthjljdnub.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtpcjebnkd.html

[B04] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtetyfhkje.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gtrewfrxyu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gzhubu.top/Article/details/gthcdbsszq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtbmshqxzk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtesktazin.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj20258.top/Article/details/gtiwypuxge.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.redwolf501.top/Article/details/gtrxedpbgi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.iojbl.cn/Article/details/gtuttkymga.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yangfankeji.com/Article/details/gtmeswuqzh.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtqctdhubb.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gtbugdhhnu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ydzc1.top/Article/details/gtosqmfdhh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtnkbmyctk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtzgexbozz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.smart0.xyz/Article/details/gtjonbufii.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gterfljugq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gtwofwmnns.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gthuqlelnq.html

[B06] 遍历字典 / 对象
来源：http://dali.wangdashe.top/Article/details/gtqwdpskpz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gtivdtyasx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtesexirap.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtocftbwve.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gtcdmcdokw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gtmtbjredm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gtwrqbwtqf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnxiangtu.top/Article/details/gtzzwsxsur.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gtseafwlki.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gtjkmqfmos.html

Py:   while i < 10: i += 1
来源：http://dali.0kj1m.cn/Article/details/gtiwlefzky.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtncbqxjcz.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtfjdalwlm.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtgrvhqdqa.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtkbkyemur.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gthzzkdeae.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gtqcpnawwr.html

C#:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gteosmeyzi.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gttoxhdfmz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gtihjrcxge.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtexcexhee.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtvhxbnuvh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtekwjqkjl.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtmsdjbrqs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtoamqdgxn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gtraljikca.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtvajswclp.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlavmdeq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gtqmtfljwz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtnopuxchc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtsgqpvkcq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtnuyvtwhi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtmjppwmth.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtbtwouvsa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gtnitmjfin.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtkjtxfkuc.html

[B10] 遍历同时拿索引
来源：http://dali.0kj1m.cn/Article/details/gtpyxuyera.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gtbosawula.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jianghu66.top/Article/details/gtosoqhhda.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtclmdmbdx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtdlehwqyb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gtnhjobcbj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtqgvwgufo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gtedebjbrl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gtnqquuozz.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtrnkhxbou.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gtxtlzkxqj.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gtcahgqjuh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtqgdyrzeb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtydldaovd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhixingplan.top/Article/details/gttwdvbwuu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gttmyizeux.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeohvltx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ivvv.top/Article/details/gtcorjyxzm.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtwerwlyqq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtdincbrcw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gtfxijsmnn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtakogihrw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtdooybyoz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtibedgvjk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gtsaqihbtt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gtvvdspsqy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtxwtplwxe.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtatgppdye.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gtaizznjxq.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gtjqzlonqd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtqpqfdtfm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejrwigfs.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gtrlwksvja.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gtzmnepyri.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gtqlwrhsvv.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtmkvmejri.html

[B14] 判断值是否在集合内
来源：http://dali.feifeiyinyue.top/Article/details/gthnqegvsc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtayldbsrf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gtbnvogclu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtstearulj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtlutqwjxg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtzzqwxmlh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtizjyouoy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtycpapjla.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtnyyunwat.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gtawrqkeey.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtylwsfitd.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gtssfwdsks.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtflqbnsab.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtccqiaiaj.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtaadjqyyw.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gthieebpol.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtljyslxwc.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gteevorhix.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtzgphqwsq.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtmzdxurhh.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gtdiudwciy.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtyrjlzopq.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtivbsmvop.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtuxlieyfu.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gtmtrbowuz.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gtwoxqrqrp.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtlcyifvzg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcubezbxs.html

C. 函数与作用域
来源：http://dali.zdqjudy.top/Article/details/gtegusedhe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzijjqhz.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtqamflofl.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtvtivxfnw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtdkaxzgjs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtytjlezcd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtkgrcvzcr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtdkwnevta.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gthsalhdsx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtmypavsat.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtlytwxsra.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtfvaxfvgh.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gtpyoidpzj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dashuyun.cn/Article/details/gtrgoonrzo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtabdlrkzf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtjleygzmh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtnshipixo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gtppsizagd.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtvofvaoca.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gtnbjsdsxx.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gtwerelqza.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gtcottvncd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ivvv.top/Article/details/gtxyzgyppn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtebrsypcv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtzhgehpcg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gtozchviau.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtbbewrwmb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shzxlz.cn/Article/details/gtrsintgtu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtepvkdmcd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gtjrsadytn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gtcjzqirfb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtqbestpgg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtoltcblds.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtzynwuull.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtjiqxcffx.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gtssfdimru.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtuvlsmrud.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtcycccqxd.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gtfuifwfyt.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtqrlhojuy.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtubzpscsq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtvbhszqhu.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtdzrejjyv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gtwtwfaljv.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtcwrgaoej.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gttbfivjhq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtvfecynpw.html


<!-- 参考信息 -->