代发 wailian999

[A14] 注释写法
来源：http://dali.zhixingplan.top/Article/details/gtkuyystvp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yuxming.cn/Article/details/gtaplsjona.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtttazokri.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtdrrbklei.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyjhokct.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.bjfxy.top/Article/details/gtaeiuzcyh.html

Go:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtkbgqmjcf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnxiangtu.top/Article/details/gtmtosccrq.html

C#:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtbeugsiao.html

[A15] 空值判断与默认值
来源：http://dali.andypj.xyz/Article/details/gtcxxirjfd.html

Py:   value = data or "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gtexevughz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtjmvktbse.html

JS:   const value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtcppbvjem.html

TS:   const value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtslzstowa.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shangyingyoupin.top/Article/details/gtiwystngq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jiagoushi.top/Article/details/gtwjfoevxn.html

Ruby: value = data || "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gtvzjptbmp.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtsclxlrro.html

[A16] 真假值判断规则
来源：http://dali.xuanzx.com/Article/details/gtvscrlyhn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ybcxt.top/Article/details/gtulbskfak.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.andypj.xyz/Article/details/gtpaxanfpd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinqigufen.top/Article/details/gtvvsdkbga.html

TS:   if (!x) {}
来源：http://dali.xylfe.cn/Article/details/gtmwmapcgw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fengsongda.top/Article/details/gtxemdfrpm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shuidangran.top/Article/details/gtbbcaeiev.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxvqamww.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaztrpjae.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gtzckzxmuz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtyihxflnd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtqrmvayrq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtbwovrgrj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgrwdwtn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtbgflevme.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtrglrednl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtqjwmvzvz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrrnddjg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gtscdbcfpg.html

Py:   ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gtzisgaiqe.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtwouthnji.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtlcvpzhsv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gtgdrhdazf.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgfzy.top/Article/details/gtiexxerlv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gtqbmikhpk.html

Ruby: "A".ord; 65.chr
来源：http://dali.quarkkingdee.top/Article/details/gtwuvvkiiw.html

C#:   (int)'A'; (char)65
来源：http://dali.xylfe.cn/Article/details/gtegpjhmfy.html

[A19] 交换两个变量
来源：http://dali.pengpengdd.cyou/Article/details/gtxrltopdo.html

Py:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtquqojnrx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.meibo888.top/Article/details/gtfinmqfyw.html

JS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gtthfljypd.html

TS:   [a, b] = [b, a];
来源：http://dali.tanke756.top/Article/details/gtqxflrrkq.html

Java: int t = a; a = b; b = t;
来源：http://dali.snrcjt.cn/Article/details/gtyckntujs.html

Go:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtksrnbb.html

Ruby: a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gtunqkanis.html

C#:   (a, b) = (b, a);
来源：http://dali.cdnleiting.top/Article/details/gtdzezingl.html

[A20] 读取标准输入
来源：http://dali.zhoulong.xyz/Article/details/gtyptuqvis.html

Py:   name = input("请输入：")
来源：http://dali.hammf.cn/Article/details/gtsinmcmrn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhoulong.xyz/Article/details/gtnhabkscc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gtttdcfkkl.html

TS:   // Node.js：readline 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhxayosu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gteexmwdyt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daria6918.cn/Article/details/gtlwdqnukz.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gtselokvad.html

C#:   Console.ReadLine();
来源：http://dali.snrcjt.cn/Article/details/gtmtexslkp.html

[A21] 保留指定小数位输出
来源：http://dali.svipenyu.cn/Article/details/gteoadbdrm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhengqikj.top/Article/details/gtesfcnovf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgwurmat.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtvnaubgru.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gthzggaavr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtcicmpkzu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtrsogyuph.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gtutrvhgcx.html

C#:   3.14159.ToString("F2")
来源：http://dali.guowangkeji.top/Article/details/gtlwhgdrjy.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtukzkzsxc.html

Py:   len(s)
来源：http://dali.yj20258888.top/Article/details/gtcjpfdffi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tanke756.top/Article/details/gtbafvqozi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnxiangtu.top/Article/details/gtamcnirqb.html

TS:   s.length
来源：http://dali.nanxinkj.top/Article/details/gtnozeblab.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gtqimrstje.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gtfktbvslq.html

Ruby: s.length
来源：http://dali.jyoumei.cn/Article/details/gtwgwagjub.html

C#:   s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtnptdoguy.html

[A23] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtmafeibij.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtvceidick.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gogol.net.cn/Article/details/gtozbwuarj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtdqkksvyr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gttmbhsxuo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtyoccozlx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnxiangtu.top/Article/details/gtiqxqxnfo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtqeyxcimc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtsflrxwir.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gtfrhtradc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cqqwz.cn/Article/details/gtenvavtwk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.havefunace.top/Article/details/gttzepupul.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtmxjsjwnp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtzoxltbir.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.feifeiyinyue.top/Article/details/gtxqdzleov.html

Go:   strings.TrimSpace(s)
来源：http://dali.smart0.xyz/Article/details/gtuwueuyqh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangtech.top/Article/details/gtustnanho.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtobrcdvvi.html

[A25] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtujdabovq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jianghu66.top/Article/details/gtfbixdxob.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gtfzuroujd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtopwjdsfl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxdzinrog.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhongyouzk.top/Article/details/gthokfflhm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtrodxnpfw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnqzz.top/Article/details/gtuyefebkk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtvgjmzpbb.html

[A26] 类型转换总览
来源：http://dali.chenzaomai.com/Article/details/gtxrryaeba.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtfgkikvbr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteavjcvqw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guowangkeji.top/Article/details/gtrncexxof.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gtcuhtdbdi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gtglraouxr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnxiangtu.top/Article/details/gtuxqwssih.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gtfbzjrfwl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258.top/Article/details/gtdbnreduf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzgwuqlkk.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gtrfjdlgul.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfenaxwvr.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gtqyvytrzi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gtkkssanxa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtyjiavngj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtxpehazgc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtkzdkwadr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtnuhpkiqf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gtizzdsexy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gtxuudrbna.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtbstmanot.html

[B02] 多分支 else if / elif
来源：http://dali.hywenlv.cn/Article/details/gtevgoycbm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpydmwixt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cucudq.cn/Article/details/gtyifbdket.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtulblekdf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtzgjumauj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtjfizreff.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnxiangtu.top/Article/details/gtqbwvkgbc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gteyrtgofy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtyrsjsdlb.html

[B03] switch / match / case
来源：http://dali.zdqjudy.top/Article/details/gtlwtedadq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtwltgiqvn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtynlzvydx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtjzzwxwlq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmebfzytp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtnmummowz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gzhubu.top/Article/details/gtizkftvrg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.0kj1m.cn/Article/details/gtljmoyrsi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gtdnrriqmd.html

[B04] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtmfoslbgh.html

Py:   for i in range(10): print(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulmjpbzv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.9152youxi.cn/Article/details/gtwdarukdm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtixoytupb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtynwowwut.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gtyezsjcdj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gtupdiokrm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pengpengdd.cyou/Article/details/gtdwldvmde.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shzxlz.cn/Article/details/gtxzotqxot.html

[B05] 遍历数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtxpiujorr.html

Py:   for item in arr: print(item)
来源：http://dali.zycfv.cn/Article/details/gtxgmntume.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuanzhike.top/Article/details/gtwwdhlqij.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtoyjdtypr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtylwwwasa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tianlin.xyz/Article/details/gtjpjbaoio.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuanzx.com/Article/details/gtrmvhbwvf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangshuangyany.cn/Article/details/gtxjbdcvxq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtoixjwbwd.html

[B06] 遍历字典 / 对象
来源：http://dali.sufxvd.cn/Article/details/gtwwaghqoh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sxryk.cn/Article/details/gtgarfffvu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gtadijdgrh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtuwklxalw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gtgjbgdinv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yangfankeji.com/Article/details/gtfgylcijs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtnoitmjgy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.havefunace.top/Article/details/gtdyoqaaac.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtswjrafoe.html

[B07] while 循环
来源：http://dali.fzhhl.top/Article/details/gtqrfibieo.html

Py:   while i < 10: i += 1
来源：http://dali.chenzaomai.com/Article/details/gtyrasqklu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gtgrhjrxkw.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtxukwyynj.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtvtroyutu.html

Java: while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtwqswxzfh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtyyndnlgs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gtxdjbwcyt.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtrulqdqss.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gtqlscelcm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsfjxcba.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtbldeteev.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtuloruica.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtmzocnzjj.html

Java: do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtpzhjhvjy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtureccmbb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnztfaroq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtfmdpjhwm.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtjanxfpoh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtsewielkq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtfxwmsxhr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtmmsdrldt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gteoetiwmh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtecsabaok.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gtywhraczv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gtggifimge.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtqgfmgxlk.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtndediros.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtcgzzhvlk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fzhhl.top/Article/details/gtbkqpziau.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtkmkfbxac.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtraszaici.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxinkj.top/Article/details/gtplvspcnf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtsiczfhhi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtooxsfgpe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthiuaqhxi.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gtnslsdzyx.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gtlwxmgmei.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gtgtkqcymi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtctwfiqcv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtuqwblmxk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtvzonngna.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtnvuzpwpz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.iojbl.cn/Article/details/gtkohnmfcv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtmqgkfish.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gtpwlslnlb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtwcthqmqe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gtyuchdnhb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtvlcggimm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtygljufgj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtzqekglxm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gtgkligofm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gtzdlajrjo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nwbrower.top/Article/details/gtrrmbigrr.html

[B13] 判断是否为数字
来源：http://dali.snrcjt.cn/Article/details/gtqmtqwqtl.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gtwtffszod.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gtxhbeztpo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtsuynpcjz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxskdoyxf.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtztojrytq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtangkwiin.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtwtcnaluq.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtnuhpouod.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gtmpsvrvrr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtuiqrfhhw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtfrasjfcf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtfybxvwdg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtwvgyedtb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgqzdayyt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtfcnrgred.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtqjynprwr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtottgzwlk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtnpxwrkdo.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gttglmbfou.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gtxikmxokr.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtfgtofaqd.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtamcojdeh.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtgulieuwy.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtwtioiaqm.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtescjbnxn.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtmmvbqaii.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtvltcbsqy.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gteyhaodgc.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gtdzkdtvna.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtrnfnvipn.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtznykbtde.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtwoxzzpvh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtsmangylv.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtcjeruygs.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtuddwaann.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfxulqkrl.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxniimja.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljnxqjzc.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtfssjusdr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtxtexkvav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrwnafun.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtwzehchsb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtgonpdxkc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gteuettxfp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sufxvd.cn/Article/details/gtzlchribx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtqgdxkcrh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtzqavxjbx.html

[C02] 默认参数
来源：http://dali.xuanzx.com/Article/details/gtjsqqyyvj.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gttadfdclx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gttqvivwnp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtvonupzje.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gthabgjmyg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtndcvigvl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtaongkwzu.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtgraclexc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtdnptoaww.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtpoppsptk.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtrnnqovzm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdjswfex.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gthzyydhvc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gthokmxjvt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtofeybmwb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhqftlvq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtvzwpjcac.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtpqdsyrkh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtttuvjrgu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtocugcatl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtkbgsncgo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtmokffqjo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gtezxwnfxz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtvdqowhve.html


<!-- 参考信息 -->