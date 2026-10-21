代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtwupncxfx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtqgghev.html

Go:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtiysafkor.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yvedp.cn/Article/details/gtuavvzzlu.html

C#:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzisakfrb.html

[A15] 空值判断与默认值
来源：http://dali.jinqigfzy.top/Article/details/gtytomlylk.html

Py:   value = data or "默认值"
来源：http://dali.ppjwa.cn/Article/details/gtunnhdgnl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gtccvpvrpm.html

JS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gttzepurvj.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gttepercxe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ivvv.top/Article/details/gtvjfdqmfo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhoulong.xyz/Article/details/gtuyxgfndh.html

Ruby: value = data || "默认值"
来源：http://dali.shuidangran.top/Article/details/gtnevomqfc.html

C#:   var value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtbdfyaqll.html

[A16] 真假值判断规则
来源：http://dali.fengsongda.top/Article/details/gtibwqijkj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtrxugxdxv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtownbhdnf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yj202588.top/Article/details/gtzfzqpmjn.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gtkyzanikc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gzhubu.top/Article/details/gttxxcrfvx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigfzy.top/Article/details/gtelwompzh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpaaczlk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangdashe.top/Article/details/gtkmaogxew.html

[A17] 位运算
来源：http://dali.andypj.xyz/Article/details/gtrfwygfnv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtqpdeksqb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daria6918.cn/Article/details/gtczkpweau.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtzboqqjyc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtbrbhffwi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtjlkmwsce.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gttwpsbmdc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtzzylllhg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtcljsdhtp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnxiangtu.top/Article/details/gtwrbcbnds.html

Py:   ord("A"); chr(65)
来源：http://dali.yj202588.top/Article/details/gtxdohgioh.html

PHP:  ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gtwuxqktft.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gtngowdyjf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gtbzhdtyms.html

Java: (int) 'A'; (char) 65
来源：http://dali.mhx1999.top/Article/details/gtispkwuvi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjndzwbej.html

Ruby: "A".ord; 65.chr
来源：http://dali.jianghu66.top/Article/details/gtsiuaepzf.html

C#:   (int)'A'; (char)65
来源：http://dali.xziqi.cn/Article/details/gtcieysola.html

[A19] 交换两个变量
来源：http://dali.aibaodan.cn/Article/details/gtevraljve.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtxbvjgvzd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.snrcjt.cn/Article/details/gtlqckautu.html

JS:   [a, b] = [b, a];
来源：http://dali.ybcxt.top/Article/details/gtkbsuwgiq.html

TS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtupbyqbln.html

Java: int t = a; a = b; b = t;
来源：http://dali.mhx1999.top/Article/details/gtcapfejnv.html

Go:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gtvhpynppd.html

Ruby: a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gtblibrtxr.html

C#:   (a, b) = (b, a);
来源：http://dali.ydzc1.top/Article/details/gtcbfmikyy.html

[A20] 读取标准输入
来源：http://dali.shuidangran.top/Article/details/gtmckwltem.html

Py:   name = input("请输入：")
来源：http://dali.yj202588.top/Article/details/gtzwsoibjn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sysykeji.top/Article/details/gtavamazua.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.iojbl.cn/Article/details/gtgmsluuqj.html

TS:   // Node.js：readline 模块
来源：http://dali.pycfn.com/Article/details/gtowjhisjg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tanke756.top/Article/details/gtauvztbpp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gtzdzvvqjv.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gtrlfgrjcp.html

C#:   Console.ReadLine();
来源：http://dali.jqgufenzy.top/Article/details/gtacttoaej.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gtviblhgok.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yuxming.cn/Article/details/gtrwmlxnng.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtcsgkjyjk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtvrtuyweq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqspudnr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtyhfdpara.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtifuczzlo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvggoebvz.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gtdpxpndyf.html

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtideluubo.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gtcedbmwil.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hysaishi.cn/Article/details/gtbgmnvsxo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtgwwelcgc.html

TS:   s.length
来源：http://dali.ehwqpu.com/Article/details/gtbkmjzwgo.html

Java: s.length()
来源：http://dali.hysaishi.cn/Article/details/gtwccmhupy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gtkerwwuck.html

Ruby: s.length
来源：http://dali.hysaishi.cn/Article/details/gtlatuhmir.html

C#:   s.Length
来源：http://dali.chenzaomai.com/Article/details/gtzxgcvgfa.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrnbyuqn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuxming.cn/Article/details/gtqkvvredp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.redwolf501.top/Article/details/gtwzdpqwma.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtkcsrarng.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gtnxmgekvs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtbjywjjvb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnqzz.top/Article/details/gtirmabukh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtcrubljtv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpfepnrx.html

[A24] 去除首尾空白
来源：http://dali.zdqjudy.top/Article/details/gtbbepdoic.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgufenzy.top/Article/details/gtzsbxhcrx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhixingplan.top/Article/details/gtuolexfqd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtcinibmrf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtypvdpkpr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangdashe.top/Article/details/gtffmdjele.html

Go:   strings.TrimSpace(s)
来源：http://dali.yanxiufei.cn/Article/details/gtawwmthha.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.andypj.xyz/Article/details/gtxfsowamv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtyedbaawy.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gthizxacyg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.smart0.xyz/Article/details/gtzdqdrbhk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmjxapwdn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnquukfwm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gtfiwcuvzm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gtfekuhyax.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gtxsjbatoq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.bjfxy.top/Article/details/gttyajgjkt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtopqzwwwp.html

[A26] 类型转换总览
来源：http://dali.hongshengwenyu.top/Article/details/gtejxqvokh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhiwuduotai.top/Article/details/gtkljgchpv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenzaomai.com/Article/details/gtufbextwa.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gtgmvpbxhk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgufenzy.top/Article/details/gtipdrinnv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtrxyakvdz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhongyouzk.top/Article/details/gtjlssfypy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gtelozftyj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258.top/Article/details/gttcbdjbds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdilyjauj.html

B. 流程控制
来源：http://dali.iojbl.cn/Article/details/gtuzwseown.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxkjsqan.html

[B01] 条件判断 if / else
来源：http://dali.0kj1m.cn/Article/details/gtdvmhixin.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxinkj.top/Article/details/gtwkssgsea.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtnressxsj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtdxmgbveo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtclhykdef.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtrvlbgwxh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangtech.top/Article/details/gteqjmaciz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtpqnrovau.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtzboeeokq.html

[B02] 多分支 else if / elif
来源：http://dali.0kj1m.cn/Article/details/gtwnmezfxh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.mhx1999.top/Article/details/gtqqpkndng.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxfbwocwy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtdgeocwji.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtfrqumszw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtglzqxogj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pycfn.com/Article/details/gtqahpryfq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjudmgtp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtxoogmsyg.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gttfvedlgr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenjidiqi.icu/Article/details/gtvnmiguwt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtbkmyhtfr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtfyfgheds.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtuqqnweaa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gttjtklfuh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gtvimbmoed.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gtrzpogobk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiazrkvt.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtqicwysfi.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gtmvlevges.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gtbxhbaawt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gtslwepntt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtiaxjrdfa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gtneiwkqaa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tanke756.top/Article/details/gtwjqaydmm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtwgbucscu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hfpthk.cn/Article/details/gtvtmmlqbm.html

[B05] 遍历数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtmlsehbwm.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gtfjxymsty.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gtqxmolszr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtfyjdpnml.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtqtijuvde.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnslgdayu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yanxiufei.cn/Article/details/gtidndhqsd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daria6918.cn/Article/details/gtuqhdsgcr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gtxptulknh.html

[B06] 遍历字典 / 对象
来源：http://dali.haohaochexian.top/Article/details/gtmpsuighr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daxiang520.top/Article/details/gtqlqmjhmx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gttxgaipky.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gteeumkivl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtwvdmavmk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gtubgkplxj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangshuangyany.cn/Article/details/gtxclkybwf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sysykeji.top/Article/details/gthpgfqshs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.c1oappe.top/Article/details/gtfgfdfvdi.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtnwjvugve.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtmdkdaaft.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtbgtaofqb.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtrspviahw.html

TS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtxnihhblz.html

Java: while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtsrxziexu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtzgdkecaj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gtfotrmcif.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrvnasusu.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gtpvioftas.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gthxtnuyji.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtvjvgocyb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtqbrdivri.html

TS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtubzxbshv.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtwtxyrdxw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gtqivyqesn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gtvwzdgcio.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvymjpdz.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtqiwnvwwi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gtvndeldbx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtdsuihpbg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtquzgobpw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtcooqsbni.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqahskpxq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtwwfcxqaj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtorkjnbvo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtbnorydvx.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gtibegrdts.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gtcptfodzi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gtnjehhpxj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtetfjanfc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtvkhuanal.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gtcpfwcgon.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.kuanghao11.cn/Article/details/gternymdeg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtylsejuyz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gtpzfskplu.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gtwyhlszli.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtxnawjrlh.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gtbkbkcepm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtlxbymuxh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtynfuwgty.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gttevviibz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtfqeefzzr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtamzsrnfe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ivvv.top/Article/details/gtcfyjowxz.html

[B12] 跳出多层循环
来源：http://dali.cheryme.top/Article/details/gtrtkooxyz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gtnnmsycql.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtokrceetk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtossiaiov.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtblwpgclk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtmmutempx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gtkdurpkmk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gtuwzwxjov.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtlkqgbrgk.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtomyoulss.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbwfvabh.html

PHP:  is_numeric($x)
来源：http://dali.ydzc1.top/Article/details/gtwetgbdyn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gtezvkbygy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtpzjnbind.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtbffxcahq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gtwmxjjiir.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtdwzjajfw.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtxkfsebkf.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gtiiygrkjg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gthpoeptfw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtnxbexwud.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtiyzdhfpk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtqomqbxja.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtqnjkuztn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxuozdmi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtrpmastwd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtgpppsaps.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gtovzpjxar.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gtvsftrgix.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gteqlfzjop.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtzaihllxn.html

TS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtvkcsovpk.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtzkejwxrn.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtmorsfetb.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtoqtgzejv.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtkehixkre.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtgraqpewq.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtuikutnwj.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gternzbcwz.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtxpvbpope.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtncykewfu.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtiscvbfoe.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gtpnscxltt.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtbbfsisob.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtsskfxeex.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvqxnewsp.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtdidgdync.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtohtmbxaq.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gtxwxcwwys.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gthlibzesp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gthzoycjxu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtwxprkqqh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtiknjzkez.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtbgdzgftc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gtfwdofqfc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtacuodbcv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gteigtifeu.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtxqxmgjei.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtxgtxxkuj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gtlepcouxc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtnpoyhqny.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtpfzffmla.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtzizzniny.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtuihlwqyb.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gthplwqaxi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtaxrrtjst.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gtkyajemwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gtlvbdgien.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtpidfjemf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtavxlpavc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtmxsdampx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gtfyeemyeg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtcdcghonb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtkbglkvav.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtqelghlje.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtniiqhwrc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcpmpqdq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtvbjdlkpd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gttdheduqp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtnkyqpews.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtmmiybxdk.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtebjvurll.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoeihmhsb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtyfqzgirt.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtfezvppxo.html


<!-- 参考信息 -->