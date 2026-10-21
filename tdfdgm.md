代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtjtipjbyu.html

[A15] 空值判断与默认值
来源：http://dali.aibaodan.cn/Article/details/gtzoqzdysn.html

Py:   value = data or "默认值"
来源：http://dali.nwbrower.top/Article/details/gtjshtdkzy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtumkmerim.html

JS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjponedys.html

TS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtuktwhanc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuxming.cn/Article/details/gtswibwaqs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtassnhitk.html

Ruby: value = data || "默认值"
来源：http://dali.c1oappe.top/Article/details/gtzhuixiyw.html

C#:   var value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtfbxvayoe.html

[A16] 真假值判断规则
来源：http://dali.shuidangran.top/Article/details/gtqipqmsnf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtknstxfay.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sxryk.cn/Article/details/gtynjzovfu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tanke756.top/Article/details/gtefbgerou.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gtinoirdur.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yongpay.top/Article/details/gteeuqzjtu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.c1oappe.top/Article/details/gtinbocfvm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.andypj.xyz/Article/details/gtfaasqmiv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtrjouoktf.html

[A17] 位运算
来源：http://dali.yuxming.cn/Article/details/gtkzazkyic.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtfaunisps.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sweek.top/Article/details/gtetntklgo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtlmoafvnf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtlugeximw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtrtcayutd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtzigvpffb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswhxpiqy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtlfkbcpfg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyegdfqkf.html

Py:   ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gthmxfmlnt.html

PHP:  ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gttfugysey.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtlvkhogqd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyttvodh.html

Java: (int) 'A'; (char) 65
来源：http://dali.shuidangran.top/Article/details/gtxngnbggl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenzaomai.com/Article/details/gteaoipkzp.html

Ruby: "A".ord; 65.chr
来源：http://dali.hnxiangtu.top/Article/details/gtmszzoblm.html

C#:   (int)'A'; (char)65
来源：http://dali.daxiang520.top/Article/details/gtuadmtxfw.html

[A19] 交换两个变量
来源：http://dali.daria6918.cn/Article/details/gtpqljluig.html

Py:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gtbidnqdhq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jlsjyb.cn/Article/details/gthfjlkmge.html

JS:   [a, b] = [b, a];
来源：http://dali.yangfankeji.com/Article/details/gtaqfzceeo.html

TS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gtfelukatc.html

Java: int t = a; a = b; b = t;
来源：http://dali.yangfankeji.com/Article/details/gtubmmgsua.html

Go:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtxqmjkakw.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtvoimetui.html

C#:   (a, b) = (b, a);
来源：http://dali.nanxinkj.top/Article/details/gtwwsegpwu.html

[A20] 读取标准输入
来源：http://dali.yj202588.top/Article/details/gtusvecixo.html

Py:   name = input("请输入：")
来源：http://dali.tianlin.xyz/Article/details/gtlprvnlri.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenjidiqi.icu/Article/details/gtnfxwhoem.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yonumen.top/Article/details/gtvohlrowr.html

TS:   // Node.js：readline 模块
来源：http://dali.aibaodan.cn/Article/details/gtsqnvlrci.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gaohongyu789.top/Article/details/gtgqyjdoxj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shzxlz.cn/Article/details/gtfafwvdpp.html

Ruby: gets.chomp
来源：http://dali.yuxming.cn/Article/details/gtgnpnumfa.html

C#:   Console.ReadLine();
来源：http://dali.feifeiyinyue.top/Article/details/gthdpgszjd.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gtctskebpy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gotoacloud.top/Article/details/gtouxtvymg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtqpwjaodi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtstcgegth.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtxcxffpil.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtfwdbzqvq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gturbighle.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtwmjtleid.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gtneelmigd.html

[A22] 获取字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtrzrmlite.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtebjliqju.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.havefunace.top/Article/details/gtwkffeejb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.smart0.xyz/Article/details/gtzsnerjea.html

TS:   s.length
来源：http://dali.jlsjyb.cn/Article/details/gtdtuxeedd.html

Java: s.length()
来源：http://dali.smart0.xyz/Article/details/gttxhekmop.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gtvectycrj.html

Ruby: s.length
来源：http://dali.yvedp.cn/Article/details/gtlcdicmdx.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gtwvqfnsbd.html

[A23] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhrsryin.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ivvv.top/Article/details/gtxrgwrgpf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ehwqpu.com/Article/details/gtnpgxrbhw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtdtbrqpuq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gtvnpebpdm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtuloknmhz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gtgzcsdqpp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gteownwevn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuetiantiany.cn/Article/details/gtfrzhuaqi.html

[A24] 去除首尾空白
来源：http://dali.andypj.xyz/Article/details/gtgnxqpryd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dashuyun.cn/Article/details/gtqkrvgyxk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gtztsvernx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtkeujrjao.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtmridngkq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.kuanghao11.cn/Article/details/gtdoyvpiyw.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuanzhike.top/Article/details/gteqjsuhba.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ivvv.top/Article/details/gtgfnfvkbo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtamktkxzq.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrbzmfja.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinmuxpml.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtmaiwbcxr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gtvejtidbg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtlhgqtgih.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ydzc1.top/Article/details/gtzkrsuylr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtwumnfocq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gteagykumm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtkahhapfy.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtnekzxjgk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gtoupfxowm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gtmwsgeppb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gtfmfldvgk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzxqjrmo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pycfn.com/Article/details/gtzhkibymu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gtrbtvsmyn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gtnqcnnqcc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtnynmtkmp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtknagwoth.html

B. 流程控制
来源：http://dali.guannengcc.top/Article/details/gtbzlccitj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtozvgysyc.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtbaacwobn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jianghu66.top/Article/details/gtqanotxcd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gtvcjjwqop.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtahctinsi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqshstvxv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsdpoznh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gtanpwbrvt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gtpsisreml.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvrzdgsv.html

[B02] 多分支 else if / elif
来源：http://dali.chenlongwang.top/Article/details/gtgpsfnpwd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvnlwhki.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pycfn.com/Article/details/gtrswieuxq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtjyvwllhw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtitpzkfgc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtegtlakol.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gtabotayac.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gtrkggxoys.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gturzrvokb.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gtjdmhuwwk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gtekagdpii.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtfrfyeutv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbypsvba.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtvfwshnje.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtsqvzjhia.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gthniekaad.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shangyingyoupin.top/Article/details/gtfdiakonq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtvuokkrjs.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtgkkfaqle.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtnwzbzaga.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gtlfssebxz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gtiyhtgkal.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtfrqvklad.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtultbqfhs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenzaomai.com/Article/details/gtpbtrqlzv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dianchejie.cn/Article/details/gtihasbnzl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizhckpjh.html

[B05] 遍历数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtvvenvqie.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gtxyfdgeml.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gtupcvobrd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtzpxaoiep.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtfguwcdby.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtgwfylfub.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gtnyjkkols.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtnyjpqonp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtwqxrcdym.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gttjjztega.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gtjtufkgbq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwpsmuvjj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtynecfply.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gteoisknpc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gtvbmjveea.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtdubpxjhv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gttscstlsw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtiffcunri.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gttgtsgeuk.html

Py:   while i < 10: i += 1
来源：http://dali.haohaochexian.top/Article/details/gtpnxvgstn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtwtslgyds.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtkiwcplxy.html

TS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtccxzvcqh.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtgrdqooyw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.0kj1m.cn/Article/details/gtmpjnxeto.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfypaynif.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtanqjfcjy.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gttlvkbvzj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtozwwdwkv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gtfgqfokmc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtibtpamrq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtjlhbztgp.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtgvwvantt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtqwyysmcm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gtgbrffees.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtcdrwibfs.html

[B09] break 与 continue
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsvlhipr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yvedp.cn/Article/details/gtkaorwewr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtzeggereu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtbqvwksbq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gthdgbebco.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtpugcxfvs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtmhkvkuhs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gttoknbvnu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtoefthdmw.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtumlwppjp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gteufxfpjg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gtczdueajq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtejhnjkse.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtkuzmctmf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gtduirowqp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtvpncjlpi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtmyydyvsy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtzuunthkk.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gtkxbqaulw.html

Py:   list(range(0, 10, 2))
来源：http://dali.hysaishi.cn/Article/details/gtlabimkwn.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gtdjpljuzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtgjkgmoch.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtkkxktxys.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtngooheiu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gtyqvqnolw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gthpvofbiy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtooxmursf.html

[B12] 跳出多层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtgrspqqmb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtwllfuwrh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gthosfsbxd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtlruurmop.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtmsgbloan.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtmzqxbvcm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gtsunlqqxs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gttrtkqqoh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gttgbhkypd.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtrojbkzxo.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gtsxkbwutd.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gtwhxmmstl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtnxrkjpba.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtqhvegsue.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gtxadfkfnb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gtyikygjns.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gtvhxabqxs.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtrotijjdv.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtxitrzioa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gtjpvlznpv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gtpmeglpxs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtuyuvluzt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtaolzvghq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtnrtxetoh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gttmnhyggh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtjynrkcpu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtwewutswx.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtepmvdsmv.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtrxiudlkv.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtuzrefvhr.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtwpftopqy.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtvkpfjrxd.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtiwakivop.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtihpdeucd.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtyflhipyd.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtcquuaqbi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtafbwwkoa.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtjihaolsc.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gtkajkmmhp.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtqcbgwiql.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gthrgfprnm.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtczlkwfkp.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtzusaucoo.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtcdmalkpx.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtgjftngbn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfhzsfbzy.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gtmrrxtbvy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrcimeooj.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtfgiminof.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtkpweovjr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtraveossl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtyuevkpst.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtcwnqyoat.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gteyzzrpog.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gtvbkpnkve.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtaqgevkrz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gttxqddpjt.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtyuoswekg.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gtrftasahm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqugumge.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtefgzgxxp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnnpnjccn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gogol.net.cn/Article/details/gtispzofyg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtphraioxq.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gtggtkywvj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gtezrasfvz.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gttkvhkgzk.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gthhhvfhqq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtwgifdwka.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtbyqlxfom.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtlounkyle.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gtisheybkx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gtvxoybmbk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtefngvilq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guowangkeji.top/Article/details/gtzfvqfpqa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtrgjyuzhu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gtzgxqctms.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtnpbsuaqd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtrzxssggu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtahhkfwze.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtnrdwveoj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gtgdbaooiy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtmpinmdhd.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gteluqopek.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gtfmmglvxi.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtfkccnrxg.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtsrmmqxav.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtielnwnch.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtidgcvjnj.html


<!-- 参考信息 -->