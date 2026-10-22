代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtvxsqjvye.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yangfankeji.com/Article/details/gtbhteupzn.html

Go:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtrbonwqte.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuanzhike.top/Article/details/gtdddgidxm.html

C#:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtmkebzmcr.html

[A15] 空值判断与默认值
来源：http://dali.yj20258.top/Article/details/gttgjvulta.html

Py:   value = data or "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpzzwbfl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtxarmaaje.html

JS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtyiigvcbr.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntnuersb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhongyouzk.top/Article/details/gtqhepytni.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gtkrzsgjao.html

Ruby: value = data || "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gtleqneift.html

C#:   var value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtwpuuxxmw.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gtsflyfwwq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtfhfirtjs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shangyingyoupin.top/Article/details/gtxzlygcty.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenlongwang.top/Article/details/gtrqhhuakt.html

TS:   if (!x) {}
来源：http://dali.9152youxi.cn/Article/details/gtbsxcubur.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtybabdhva.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuetiantiany.cn/Article/details/gtuqsmdsre.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjxunqap.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tanke756.top/Article/details/gtpqfoouvj.html

[A17] 位运算
来源：http://dali.ydzc1.top/Article/details/gtvdjsvrwu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtqvtmwjym.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.andypj.xyz/Article/details/gtwkidygve.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtjwbmslyb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtihcwizrr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtkhoteugi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtcbnluwzc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtbkvnboxr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtejlcqejv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhengqikj.top/Article/details/gtxmnsqnuu.html

Py:   ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gthzfnpgmp.html

PHP:  ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gtteywatdm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gtorjoxhli.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gtgekptcwm.html

Java: (int) 'A'; (char) 65
来源：http://dali.hfpthk.cn/Article/details/gtzzptafur.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nwbrower.top/Article/details/gtafdotzxt.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj202588.top/Article/details/gtimqbvtuw.html

C#:   (int)'A'; (char)65
来源：http://dali.yueranfly.top/Article/details/gtvrvuipak.html

[A19] 交换两个变量
来源：http://dali.cucudq.cn/Article/details/gtwaktkujd.html

Py:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gtpsebilzg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ivvv.top/Article/details/gtxolmckcx.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gthojumprz.html

TS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gtuthjbeod.html

Java: int t = a; a = b; b = t;
来源：http://dali.dianchejie.cn/Article/details/gtrhvnenoc.html

Go:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gtggjowrwk.html

Ruby: a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtlbmxwysm.html

C#:   (a, b) = (b, a);
来源：http://dali.zhoulong.xyz/Article/details/gtxaduiykq.html

[A20] 读取标准输入
来源：http://dali.zycfv.cn/Article/details/gtozqstags.html

Py:   name = input("请输入：")
来源：http://dali.yuxming.cn/Article/details/gtzwngznkw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuanzhike.top/Article/details/gtdkreyfek.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenjidiqi.icu/Article/details/gtzeejjrta.html

TS:   // Node.js：readline 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtjxavys.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xinyue.icu/Article/details/gtifshyyrn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhiwuduotai.top/Article/details/gtdtkkmstj.html

Ruby: gets.chomp
来源：http://dali.fzhhl.top/Article/details/gtfinmqinj.html

C#:   Console.ReadLine();
来源：http://dali.zhengqikj.top/Article/details/gtbyfwibmc.html

[A21] 保留指定小数位输出
来源：http://dali.fengsongda.top/Article/details/gtdvvrimpg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ydzc1.top/Article/details/gtoragzlnl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtulgqozov.html

JS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtofvxutng.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtlrgnmq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gtunmomguz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtasxvctua.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfwscgiu.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhiwuduotai.top/Article/details/gtbhceoeyh.html

[A22] 获取字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtzcxhgdtu.html

Py:   len(s)
来源：http://dali.bjfxy.top/Article/details/gtpwychisb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxuanxn.top/Article/details/gtlzgdkkcm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhoulong.xyz/Article/details/gtkbuhxrsp.html

TS:   s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtnokyatvr.html

Java: s.length()
来源：http://dali.fengsongda.top/Article/details/gtebfreqnh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hammf.cn/Article/details/gtrozrlire.html

Ruby: s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnsgxriy.html

C#:   s.Length
来源：http://dali.zhengqikj.top/Article/details/gtzrcxyuvg.html

[A23] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtnscdzpvi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tianlin.xyz/Article/details/gtrmexdvzm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.havefunace.top/Article/details/gtlchzqccz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtvswwppfa.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtbzzjvphb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtvqpaachq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gtfnzcavah.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtkoqrnght.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrxklegp.html

[A24] 去除首尾空白
来源：http://dali.haohaochexian.top/Article/details/gtvdawmvwk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cashguo.top/Article/details/gtyqlfwreq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenlongwang.top/Article/details/gtugwbdptr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gtehgemtzu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtnbohjsgm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yongpay.top/Article/details/gtnmxzyvyb.html

Go:   strings.TrimSpace(s)
来源：http://dali.jianghu66.top/Article/details/gtqtypzeub.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guowangkeji.top/Article/details/gtmppbyqoa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gtppubwydi.html

[A25] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtxuifmdmw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tanke756.top/Article/details/gtygmjgjev.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jiagoushi.top/Article/details/gtnepxagyq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gtpualrxec.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gtjfusxmhe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtkrtzycsa.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtnvudjafy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtabkruizg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtxrzulkcz.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gtyyllcznf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yvedp.cn/Article/details/gtqumhsubn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gtkxxujhal.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gttjjktnsx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shangyingyoupin.top/Article/details/gtgkxqshwb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvnfhmvf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sxryk.cn/Article/details/gtnbuuziqx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gtbasszayi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtkjbmubpl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteqnbdztz.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gtwmerrvok.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjucmcbph.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gtumizzpkv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtyskusaty.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmvvhzazk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gtcbqaauqg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtpwylihhh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gthkqcsvoq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gtiuolhzkv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gtkabuhvka.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtcidmcpfp.html

[B02] 多分支 else if / elif
来源：http://dali.sweek.top/Article/details/gtpezketga.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sxryk.cn/Article/details/gtqkzggadw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gttfomoitw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gthwfstrpx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gttmsgtjic.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtmtxsxolx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gogol.net.cn/Article/details/gtffvyygzp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.9152youxi.cn/Article/details/gttmoeqetk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtaifhaazg.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtdtybpdyh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhiwuduotai.top/Article/details/gtcvudckyo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtjvuyjozf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtccwvjsng.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmzwnhpyf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtvxukwfov.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtxukemsho.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hfpthk.cn/Article/details/gtzimnqbsi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtrkujibex.html

[B04] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gttpclobmv.html

Py:   for i in range(10): print(i)
来源：http://dali.xinyue.icu/Article/details/gtbervnkzb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guowangkeji.top/Article/details/gtrlqptzor.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtstbqjlvt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtdbbqvbne.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gtbhetfajd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cdnleiting.top/Article/details/gtbsycefal.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gtwcumsrpr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ydzc1.top/Article/details/gtztuezpmj.html

[B05] 遍历数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtjwrfukwh.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtgvnvbacq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbuzsrwkw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtmugupyvl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtzsdzbfwg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.andypj.xyz/Article/details/gtdtdxoxvy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sweek.top/Article/details/gttuxyytsw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aibaodan.cn/Article/details/gtkhgdujkh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gtnmypemqi.html

[B06] 遍历字典 / 对象
来源：http://dali.mhx1999.top/Article/details/gtovbaiult.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhiwuduotai.top/Article/details/gtbmwsgmpu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yueranfly.top/Article/details/gtdrlddcgk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gthaypmhjw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtcaktqerp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangdashe.top/Article/details/gtpjgigpvk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hfpthk.cn/Article/details/gtkzlfybpf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gtiehejrmr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtenrupsry.html

[B07] while 循环
来源：http://dali.ppjwa.cn/Article/details/gtakklzwtm.html

Py:   while i < 10: i += 1
来源：http://dali.shuidangran.top/Article/details/gtapvkjlnt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ydzc1.top/Article/details/gtoqrtgpsz.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskeoaujt.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtujqbjijk.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtpckrxltg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhongyouzk.top/Article/details/gtvmihdehz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtynhlgwlu.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtvewvjzot.html

[B08] do-while（至少执行一次）
来源：http://dali.wangshuangyany.cn/Article/details/gtiogumodx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtcpvgzeup.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gtcojsoanc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtxechmnsp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtknqdqpbw.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtudkidcpk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtetxjnrmw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.kuanghao11.cn/Article/details/gtlkdrreec.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtyzhsfpos.html

[B09] break 与 continue
来源：http://dali.fzhhl.top/Article/details/gtwmxyurbv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtroyjjiwf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtibeupnry.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtzsdexnos.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxdnlnmnd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtaioddzub.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtpzypfzai.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xziqi.cn/Article/details/gtphbjgujv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyfmcntui.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtapyfsvai.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gtjtujftcn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigfzy.top/Article/details/gtzlxnarvj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtqefeeyev.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtzfqqeyaw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gtcqcnfczk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gtxmywtuqm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sweek.top/Article/details/gtyaxftkxl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gtbjemsgup.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtfkaesgqh.html

Py:   list(range(0, 10, 2))
来源：http://dali.yangfankeji.com/Article/details/gtgnrrcymc.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigufen.top/Article/details/gtwzpptgof.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtnpdwlyts.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtzwhbsqth.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gtynkrkxim.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gtbucjyypd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gturdarios.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gtbkerlpih.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gttvatanvb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gteutrgwny.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtffdiahmh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtdwmekcbw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmdznwhw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtrcukvcns.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gtqdrzayxw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gtnzodqpep.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gtlxorzzcb.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtnmjprnbt.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtcjhmqkfj.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gtbtxvjngk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtqqzcpods.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtdgafwxfh.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtmsfpcoet.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gtykwjhrgh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xziqi.cn/Article/details/gtdiskgnnw.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtavgwxgit.html

[B14] 判断值是否在集合内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrehttpa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gtgsklryrm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtfrsiwobc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaxthjmx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtpmduhmrg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtuzobxhqf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gtjaobcmnz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gthfkrmqhe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtezhlhzre.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gtgwqhqzho.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbrqnusw.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtbujertsk.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtfimqyvge.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtkkxqgjqc.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtgqzpuqhi.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtdpwnovwt.html

Ruby: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtxbqkluuv.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtkggdzqfy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtxjbmiykx.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtpprmsgdx.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjgkoxoqn.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtfiwonokg.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtmkfkfjkt.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gttfmcvlil.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtqjfckavn.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gtkehmotbk.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtapxroiwz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtiikelsrt.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtpvquhinu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtupwpwwmq.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtwphyqhtl.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gttglagqto.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtadvojplo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtwowqnads.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtdpizbpat.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtxolvncrv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtyxaxgdmt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.andypj.xyz/Article/details/gttacltqkv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtnpnatyvb.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtukumxqov.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gtixhioazy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtbhvgqadv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gttpoofqnh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtxtviolav.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtcksprybj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtkmevdhbm.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtmqgjbggz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtcjfoxbsw.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gthbqjrcia.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gtbbpsspgr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtiahvhfzb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtoeejkwkw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtmstdjxof.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtafemlqpg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gthuihomov.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtmnrgskqv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yangfankeji.com/Article/details/gtkvtfcnnl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtqmatgrjt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gthkaakaby.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gteuevqglt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtezqeymyd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtshfuoe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gtagiewofx.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtllrhjeoc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtruknkfvc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtqfdbsxiv.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtgofnsvra.html


<!-- 参考信息 -->