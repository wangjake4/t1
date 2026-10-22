代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtvizhapuu.html

[A15] 空值判断与默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtkxyxxgfz.html

Py:   value = data or "默认值"
来源：http://dali.gogol.net.cn/Article/details/gtnzcpkswp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtiucxuong.html

JS:   const value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gthynsbzld.html

TS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtdajdzvfx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daria6918.cn/Article/details/gtuywtztaq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gtrpnxtqhm.html

Ruby: value = data || "默认值"
来源：http://dali.zhixingplan.top/Article/details/gtanbdrioo.html

C#:   var value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtnxzkkstb.html

[A16] 真假值判断规则
来源：http://dali.gzhubu.top/Article/details/gtjzpjrqbh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aibaodan.cn/Article/details/gthvyxgqmt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ehwqpu.com/Article/details/gtafbpcmgi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xinyue.icu/Article/details/gtirnxkbjb.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gtbvfzxsrq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sweek.top/Article/details/gtocvkrdmy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.fzhhl.top/Article/details/gtpspvpnaj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.guowangkeji.top/Article/details/gtzgfmsxuk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xinyue.icu/Article/details/gtobqxmcyt.html

[A17] 位运算
来源：http://dali.wangdashe.top/Article/details/gtpubrdubc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtikogpqvh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nwbrower.top/Article/details/gtrwbiilry.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtyftstlzk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtqkpsvydw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgdrxmel.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtocrgilmu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtwzqedtgj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtbaehptvq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yvedp.cn/Article/details/gtraduhjrj.html

Py:   ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlbfnebk.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gtxvoktmmz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yanxiufei.cn/Article/details/gtfvlixdna.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gtjiadtecu.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnqzz.top/Article/details/gtjkifjpmm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jlsjyb.cn/Article/details/gtyvvqcfkp.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gtlelykymf.html

C#:   (int)'A'; (char)65
来源：http://dali.fzhhl.top/Article/details/gtepytbdps.html

[A19] 交换两个变量
来源：http://dali.gaohongyu789.top/Article/details/gtorqbswlq.html

Py:   a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gtvwoaqlhw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.fzhhl.top/Article/details/gteyzkfgsq.html

JS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gtcxylmnhq.html

TS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gthcuxnnmb.html

Java: int t = a; a = b; b = t;
来源：http://dali.zdqjudy.top/Article/details/gtpblkkewo.html

Go:   a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gtdivfclyp.html

Ruby: a, b = b, a
来源：http://dali.yj20258.top/Article/details/gtuidtmccr.html

C#:   (a, b) = (b, a);
来源：http://dali.jqgfzy.top/Article/details/gtikfiljvr.html

[A20] 读取标准输入
来源：http://dali.svipenyu.cn/Article/details/gtdkitnhdl.html

Py:   name = input("请输入：")
来源：http://dali.nanxinkj.top/Article/details/gtgttjmsnp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gtwmyuxnkv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangdashe.top/Article/details/gtvqgqxrrc.html

TS:   // Node.js：readline 模块
来源：http://dali.svipenyu.cn/Article/details/gtplxtbiac.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pycfn.com/Article/details/gtlfjsykha.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yvedp.cn/Article/details/gtokywpmzc.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gtitnubzuv.html

C#:   Console.ReadLine();
来源：http://dali.nanxuanxn.top/Article/details/gtbykcgetp.html

[A21] 保留指定小数位输出
来源：http://dali.meibo888.top/Article/details/gtqileshxe.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gtwnbdywkp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuebgfza.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtcxizvnqi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtowyjlucj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtvhynomid.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtvadaparr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtekiovaew.html

C#:   3.14159.ToString("F2")
来源：http://dali.sufxvd.cn/Article/details/gtdslmjwyx.html

[A22] 获取字符串长度
来源：http://dali.cheryme.top/Article/details/gtmdciexxc.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtsvdhlwdj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gtstkdhfhg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fzhhl.top/Article/details/gtnyfagvhx.html

TS:   s.length
来源：http://dali.aizwys.cn/Article/details/gtgksvwzvw.html

Java: s.length()
来源：http://dali.daria6918.cn/Article/details/gtmgnysvme.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.vqdsnc.cn/Article/details/gttomaviji.html

Ruby: s.length
来源：http://dali.guowangkeji.top/Article/details/gtraoxdnhr.html

C#:   s.Length
来源：http://dali.ivvv.top/Article/details/gthwonqdam.html

[A23] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtchsnfdst.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfikeckm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gtteevfksg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtmnwktbql.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigbzqpgf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gtyoijygnb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtbecdimpc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtfbhoussh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yonumen.top/Article/details/gteziyiyte.html

[A24] 去除首尾空白
来源：http://dali.zhengqikj.top/Article/details/gtchgiupkl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cucudq.cn/Article/details/gtpykfkyoy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.9152youxi.cn/Article/details/gtmwmilmvw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtbvxauexy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtmhkxfluo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gtsghzinir.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gtcxsotdea.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangdashe.top/Article/details/gtlsjzcbvk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhixingplan.top/Article/details/gttgxezsoh.html

[A25] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtkucsuzyp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.feifeiyinyue.top/Article/details/gtsmfkmpgj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gaohongyu789.top/Article/details/gthoposgxo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gtmrlzjhnu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtovglmyxf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgfzy.top/Article/details/gtljygbovb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtzmbamswq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yvedp.cn/Article/details/gtlvvgkbzd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtcdlyqqab.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gtffbaavov.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sweek.top/Article/details/gtjgmkaidp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cqqwz.cn/Article/details/gtknculosv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zycfv.cn/Article/details/gttywozsds.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gtxybzkkxr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gtdddeuxrv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sysykeji.top/Article/details/gtsllifrjy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapbxabla.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtlgzcpivr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjtdunwda.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gtsmwjmycz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyexylkmz.html

[B01] 条件判断 if / else
来源：http://dali.hfpthk.cn/Article/details/gtkwilspyy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gtpxqlegxo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtbotmzksd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtvtbatfmk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtbzqxugle.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtspattqto.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gttgrthxqx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gthttayzja.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtwzheicgt.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gtchuggqib.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258888.top/Article/details/gtabjkdykq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.redwolf501.top/Article/details/gtngliyzgq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtsssxceqr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtoorhnkuz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtimrckdka.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.316326.xyz/Article/details/gtvcicimui.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gtvjbdcbzl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtncnhqtai.html

[B03] switch / match / case
来源：http://dali.jianghu66.top/Article/details/gtdxhdgtzm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gtefadilqh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjfkdkfm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtyouqjgud.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gttxnhnqtf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtdccazlss.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gtdatuuinx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtqmqiydeo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.316326.xyz/Article/details/gtxifbcgmd.html

[B04] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtwggziubf.html

Py:   for i in range(10): print(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtryshjzos.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aibaodan.cn/Article/details/gtcpswoyhc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtbxifhhpa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtuacwvsqp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.c1oappe.top/Article/details/gtklptjllq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gtgjjuqmws.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gtzmytymvf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtawxdgzdb.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtxmzphajj.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gtfamlmjrr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cashguo.top/Article/details/gtqgcvcnew.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtewephudb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxhvvorjb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gtzkqfdffx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gtoflzchcm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jiagoushi.top/Article/details/gtwcaceuqh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tanke756.top/Article/details/gtcxfmikmc.html

[B06] 遍历字典 / 对象
来源：http://dali.gotoacloud.top/Article/details/gtljnyldka.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gtszhxmxkb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yueranfly.top/Article/details/gtnmqgnvwr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqappylbi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtscatdyhi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gtbtgnrrpn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gtoefhdywz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gtmsnufwvg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gtccxrgbar.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gtzrtxcxkb.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gtqhbbbwti.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gthhwbihpj.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtakzzhivi.html

TS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtxuporjiz.html

Java: while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtpqnkrwyf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gzhubu.top/Article/details/gtmvbeplpq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtztwrzafu.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtnthapetm.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gtpgafehhe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gttdbbeeua.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtowyvmqjv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtasxsekwt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttatfmpam.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtbbwmtjnd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtqcvalslg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gtdakcgzzj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwfzegkn.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtqfdxzpgz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gtucfmfjcc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtlohiuhvx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtfddjtyxf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gttwrbkolg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbisrjaia.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtswpxyhvw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gthtmrumzd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtrgaszonq.html

[B10] 遍历同时拿索引
来源：http://dali.yanxiufei.cn/Article/details/gtouozprwu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gtbuuhsxxx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtjkdwtvnn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtxictlvpo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtgvyqezzz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gtpzmanamc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gtaqzuycne.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gtxewzokxt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gtpghzevil.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtmamgqpds.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtorspuksv.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtmjgfyizq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gttrlzvhfp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtgudhdeic.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gtxoqowbuq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtwpscofef.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhixingplan.top/Article/details/gtwzzqplgo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gtqwufnkrr.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gthhpipzkz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gteawzpyev.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtcwpmadtu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtggpgghmw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gthnpjxkhv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtxazpcljz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gttlcwralt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtizrrikqm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtzjjiarln.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gtcvnbnnqx.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gtvoubhiqu.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gtwnlejrmx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtifxuuzfq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gthbkpsvdk.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gtyzdyevqg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gtfpcedyhn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gtzvvnqjcv.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtxxjjboag.html

[B14] 判断值是否在集合内
来源：http://dali.yongpay.top/Article/details/gtcgdqaeem.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gtorvhnaoh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gthcjaelwb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtaarowtdl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtldiqdkmg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtenrwbfat.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtssxouqyj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gtlrdcmwvs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtfjstirpm.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gtqooihkbg.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gtghczklmt.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gtdwskgczr.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtuubyftkp.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtyalxrkab.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtccaqlwya.html

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtmrqiglrb.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtiiiwhzzf.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtdanzoxzd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtszbdzedf.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnkulums.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gtcyewihqn.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtfhrbvdyb.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtlxnkysdm.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtgrfgrwyw.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtqwhdvubj.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtdgvbxfaf.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gteksonfoc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtydvootka.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwcbsave.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqzxfkwib.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gteljyqdti.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtzikhuckd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtbpfdnuzb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtyrpwrsdy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtigfeohge.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtqodwcscy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtibdxteio.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtbehseydx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtnmeglnob.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtneyunilc.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gthiqqkewe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtkbpnncin.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkywlignr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtvrebpoag.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gttgldlwcs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtrbpbxzmd.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtxwfdpqaa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gteruhryfz.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtjnewqjsf.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtjgmudahx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtzdaicsds.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtkclmyzxg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtmdhijknn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtbtfzgdsh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gtajyhbgvq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtcrqmayzj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtwkqnkqmv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtyzjwgpnd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtmdxrcdgc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtduobvhsq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtrbdzmymr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtjnixrpwd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtwvvnrzeu.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtdjvzjknc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtbhhykyps.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtizubyglj.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gtdptvyoze.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtlpxudqed.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gttgxstxrd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtjjkcghqv.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtksvwdamn.html


<!-- 参考信息 -->