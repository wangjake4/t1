代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtpameevag.html

[A15] 空值判断与默认值
来源：http://dali.yangfankeji.com/Article/details/gtefwvafoh.html

Py:   value = data or "默认值"
来源：http://dali.yueranfly.top/Article/details/gtjvqntghp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtxlnqtdgw.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtlgcwxmys.html

TS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtedlridjr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tian-w.cn/Article/details/gtyduphodf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gtijqaikuq.html

Ruby: value = data || "默认值"
来源：http://dali.svipenyu.cn/Article/details/gtarfucqui.html

C#:   var value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gtvdtcenui.html

[A16] 真假值判断规则
来源：http://dali.tianlin.xyz/Article/details/gtydrgvzil.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.bjfxy.top/Article/details/gtmervlpgq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sufxvd.cn/Article/details/gtxeeuckzf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinqigfzy.top/Article/details/gtdndqhrpu.html

TS:   if (!x) {}
来源：http://dali.fengsongda.top/Article/details/gtezovwpel.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dianchejie.cn/Article/details/gtuaidolow.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.smart0.xyz/Article/details/gtvvfcnpti.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daria6918.cn/Article/details/gtmdogahkw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtzhegfoiv.html

[A17] 位运算
来源：http://dali.xinyue.icu/Article/details/gtvrkvgsux.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtihpjjgxi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtlusnlmwo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtezwzjesr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtuzeklhqr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtclcaxqhk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtorijizha.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtzgqxahmg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtoagobdwc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jlsjyb.cn/Article/details/gteookarqv.html

Py:   ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtjevlkkct.html

PHP:  ord("A"); chr(65)
来源：http://dali.9152youxi.cn/Article/details/gtgrbgsdjz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhrvqgft.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shzxlz.cn/Article/details/gttcfsqhuf.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuanzx.com/Article/details/gtmazxmecr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.quarkkingdee.top/Article/details/gtuzbavmvg.html

Ruby: "A".ord; 65.chr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjvzbgjw.html

C#:   (int)'A'; (char)65
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllfcqerl.html

[A19] 交换两个变量
来源：http://dali.nanxuanxn.top/Article/details/gtpmukazug.html

Py:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gtgqtrgxoe.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pycfn.com/Article/details/gtkzbvzrvb.html

JS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtwcpwvcek.html

TS:   [a, b] = [b, a];
来源：http://dali.jlsjyb.cn/Article/details/gtwroauugc.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxinkj.top/Article/details/gtiuacaxvi.html

Go:   a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gtunrtuqks.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtbfzyefad.html

C#:   (a, b) = (b, a);
来源：http://dali.hywenlv.cn/Article/details/gtynuxdnfb.html

[A20] 读取标准输入
来源：http://dali.nanxinkj.top/Article/details/gtxuwfjlmu.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gtunmoxcnz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gtjqcnxqwf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhoulong.xyz/Article/details/gtnohnzxox.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gtvboeyujk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuanzhike.top/Article/details/gtpxcfcmok.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hfpthk.cn/Article/details/gtsanglwwo.html

Ruby: gets.chomp
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqejseex.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtnyxodkax.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gtksbmizhd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ybcxt.top/Article/details/gtgbqwsbzu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtvpttombr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtxmdihdnm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrhcwhzww.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gthixwxkzb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtxvvgtqpu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gthozybslj.html

C#:   3.14159.ToString("F2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtydojwt.html

[A22] 获取字符串长度
来源：http://dali.daria6918.cn/Article/details/gtlfgpvbzf.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtabunkgko.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tanke756.top/Article/details/gtpiznlpsh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pengpengdd.cyou/Article/details/gtsbmldoqc.html

TS:   s.length
来源：http://dali.sufxvd.cn/Article/details/gtuxtbaqfm.html

Java: s.length()
来源：http://dali.chenzaomai.com/Article/details/gtflccclcd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jianghu66.top/Article/details/gtsnctlzze.html

Ruby: s.length
来源：http://dali.aibaodan.cn/Article/details/gtllzzjarb.html

C#:   s.Length
来源：http://dali.jiagoushi.top/Article/details/gtgxjrmyll.html

[A23] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtjzclfieb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddbzlaya.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guannengcc.top/Article/details/gteinxpvkk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gtkenhwmes.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gttfvlesvt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtiewedvbe.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.iojbl.cn/Article/details/gtzbaqqtpq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tanke756.top/Article/details/gtlmuqppqs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhiwuduotai.top/Article/details/gtocoljvyd.html

[A24] 去除首尾空白
来源：http://dali.guannengcc.top/Article/details/gtzmiybrpe.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sweek.top/Article/details/gtszgsldqz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gtvrcvsbsl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gttzbabrvg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtuddpfswb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gtjjmpqwff.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdpnoosxg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gtziadtani.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtntprxpop.html

[A25] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtmnbujhxx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cucudq.cn/Article/details/gtlrhtmprs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gtywtsjfpn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtkhtuhzdj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtnobmgjij.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtxiltpntu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtbkwlsmdh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yueranfly.top/Article/details/gtrogcrpnf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtbicmtwhv.html

[A26] 类型转换总览
来源：http://dali.c1oappe.top/Article/details/gtwsgsqjws.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfbprkeg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yueranfly.top/Article/details/gtrmdamhex.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jyoumei.cn/Article/details/gtdqfnkpma.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gtdtzrkiip.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cashguo.top/Article/details/gtijxepzww.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.bjfxy.top/Article/details/gtsftrpeyu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daxiang520.top/Article/details/gtfdistfpk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtnmmphdtt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvkhikmaf.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gtqhnavhph.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxkfyeedj.html

[B01] 条件判断 if / else
来源：http://dali.ydzc1.top/Article/details/gtgwkimpgj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jianghu66.top/Article/details/gtsfvudbvb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gtttzlhnqg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtylitfkiv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtkykfawuk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtzmrivhjf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.meibo888.top/Article/details/gttyqwwigo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyiabcim.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtjepoqwqy.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gtlveriwzg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ehwqpu.com/Article/details/gtromlxpmg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gtwlkhvgdh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtjfuigqsm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtlaxehivb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtttvxjoqh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxuanxn.top/Article/details/gtajegcwye.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangdashe.top/Article/details/gtvbkimueq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtcnkjzuah.html

[B03] switch / match / case
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjhfdcfi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hammf.cn/Article/details/gtdmdexofs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtzltianuj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtojywjena.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtdnxeouuu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtmwtksnep.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtpgflijuy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gtoqhxkqnj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtfnvtedlg.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtriszkmws.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gtcpqoqjbr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gtkhgwwuij.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtjokjcgsu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gtuhsbpape.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gtmakilryu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xziqi.cn/Article/details/gtvcrbksfw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gtnpremwuq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cdnleiting.top/Article/details/gtlspjctqy.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtkbgypspz.html

Py:   for item in arr: print(item)
来源：http://dali.hfpthk.cn/Article/details/gttafuytti.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jiagoushi.top/Article/details/gtpjityftd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtfhfqgjql.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtcxmbdzos.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrdguttcu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.316326.xyz/Article/details/gtwruqdave.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtlkgbrgub.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtwqqpmwse.html

[B06] 遍历字典 / 对象
来源：http://dali.sufxvd.cn/Article/details/gtvzdibqva.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.vqdsnc.cn/Article/details/gtldjnttcg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gtkswovjnk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwanxhrem.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtrlttdjzj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgiqdxcax.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gtfjwwfqrz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gtrcauxptb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jiagoushi.top/Article/details/gterkprusz.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtcxfmlokk.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gtswxexiio.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuanzhike.top/Article/details/gtpbcsrpoq.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtyprovgsa.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtosbohkjv.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtofebnrtz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtujuneaxy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zdqjudy.top/Article/details/gtlcaocrvc.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtjkwcvcqd.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gtzhzisasd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gtqerpfmrm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.smart0.xyz/Article/details/gtlmulpnbi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtpssmoxlb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtfzmndiso.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtyrphfdpx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtcphtvrys.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gtjcvubjid.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gturdixapt.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtnwzrbtwd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gtnsgdatef.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtfnbqqybs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtbtwixeup.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtjpnlqcxz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtftcnnyip.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtqjymjric.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtioxuzlco.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtzkprrfkc.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gtqyimxfpq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gtstzlskui.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gtniwlpvid.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtnfvppner.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtpzojmhoa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmstgxqtp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhuxrfij.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gtladcqpij.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gtgviuvons.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtmszdzzwe.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtlwrmdptw.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtexslmxzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtgbanearn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gttzspcuqq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtvzgpdlvz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtnbvpywmj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhixingplan.top/Article/details/gtekuarszc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtvnmmkqiq.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtvqlqhzho.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtwrzmnaei.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gttpmmyieg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtukywxvks.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gttbqvilkp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtntyccuke.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.bjfxy.top/Article/details/gtfmkbrhcm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtekqdkapa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtzzuixest.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtbpgqqsvh.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtmvxhefzj.html

PHP:  is_numeric($x)
来源：http://dali.tianlin.xyz/Article/details/gttebsrsxm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtamldwdtk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtwwzbhuxx.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gtypbkfrve.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtotwolqfd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtdwftbsji.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gtejbyspye.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gtxipzalma.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtxwzmtrrp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtdndjgzqv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtgbepucdt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtaacpetfw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtsytsevzi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gtdalqirhh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtbpqcqyoa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtcjddktfs.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gthjpulzbs.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtyzoifhtd.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gtaofmrvbg.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtogydtikt.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtxqncpgqi.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gttezzcesx.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjmlmobdi.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtnyytokvj.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtjlxdwzoy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtbkcpfqjq.html

Py:   if not data: return
来源：http://dali.gaohongyu789.top/Article/details/gtwpfbwsmt.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gtbrmdzfbe.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtududotmm.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtrybjtnfy.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtauzjtqzv.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gtxpxtvrra.html

Ruby: return if data.nil?
来源：http://dali.c1oappe.top/Article/details/gtlpihzqwe.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoymepei.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaihmbdqv.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gttxwqxpwu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtruurnjuz.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtieoltseq.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gtqfklspuy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtjljgjdee.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtjcyfbafc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtmoikbmmn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtosqijhkd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtydxpbyyw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwcutiro.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoniejfl.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gttvflnfbt.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gturcsbrtt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gthabcevxq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtztqhawnf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtgcpvnbhm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xziqi.cn/Article/details/gtvjfampvl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtrdhflwoe.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gthnkjsfhj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gthmojzpzk.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtdhurifnx.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gthirflmzg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gtktvtsyjf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtggjvdzfi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtwhmqonjz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbeqzjaw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtofukdevm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gtidblxiew.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtmzzxpgix.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtjqcdzepa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtoqdkumof.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtascworbu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtbxxmuqvs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtazubgwtb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gtsuzdehgt.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gtblbgtxjm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtzthlekww.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuuswdzz.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtfpryqsrd.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gthlhgrosf.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtpltdwoan.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtqlxkkrjg.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtvkdyhzhu.html


<!-- 参考信息 -->