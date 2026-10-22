代发 wailian999

[A14] 注释写法
来源：http://dali.quarkkingdee.top/Article/details/gtggffhjjl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tanke756.top/Article/details/gtqiinhwki.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gthrbwosbv.html

JS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtgnhvmjkd.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtwkdknqfr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hnqzz.top/Article/details/gtxbtzcwpc.html

Go:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtcspvncuh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.snrcjt.cn/Article/details/gthewghulp.html

C#:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtvsfystyr.html

[A15] 空值判断与默认值
来源：http://dali.shuidangran.top/Article/details/gttniytcee.html

Py:   value = data or "默认值"
来源：http://dali.cheryme.top/Article/details/gtzqeosqbh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtbggavgxb.html

JS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtwzeqttss.html

TS:   const value = data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gtpbnojcch.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.meibo888.top/Article/details/gtmntjllgg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.dashuyun.cn/Article/details/gtoeipeypr.html

Ruby: value = data || "默认值"
来源：http://dali.cheryme.top/Article/details/gtmprphtbs.html

C#:   var value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gttdfofogj.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gtzeuuhjvd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yangfankeji.com/Article/details/gtxmgahzzv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.haohaochexian.top/Article/details/gtmltbzziu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxuanxn.top/Article/details/gtilhvnvcx.html

TS:   if (!x) {}
来源：http://dali.zycfv.cn/Article/details/gtgllaarsn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangdashe.top/Article/details/gtzkkikapa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shzxlz.cn/Article/details/gteptymgdc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigfzy.top/Article/details/gtvoztxdth.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sxryk.cn/Article/details/gtsxjffjso.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gtnznozfmo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtykskgpuv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtawoxgizn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gthqgendpb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtjlciivhv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtehamjwlt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtwrcwgfnj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtetwtfspu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtcuncwyfs.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jiagoushi.top/Article/details/gtrcmryypw.html

Py:   ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gtxjoydpsj.html

PHP:  ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtsguqfqdp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtcjvuphca.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtytozrczq.html

Java: (int) 'A'; (char) 65
来源：http://dali.yueranfly.top/Article/details/gtsedxweur.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzscheih.html

Ruby: "A".ord; 65.chr
来源：http://dali.yueranfly.top/Article/details/gtgakfiyvr.html

C#:   (int)'A'; (char)65
来源：http://dali.kuanghao11.cn/Article/details/gtmkpgrxqp.html

[A19] 交换两个变量
来源：http://dali.ehwqpu.com/Article/details/gtgmkyjcro.html

Py:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtkcvmkxqt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.redwolf501.top/Article/details/gtmiisercg.html

JS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gtdiqaiinp.html

TS:   [a, b] = [b, a];
来源：http://dali.aizwys.cn/Article/details/gtmbiljsrz.html

Java: int t = a; a = b; b = t;
来源：http://dali.gogol.net.cn/Article/details/gtowjszbcn.html

Go:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gttbhzittz.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gtfnwjrcsl.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtybisxonf.html

[A20] 读取标准输入
来源：http://dali.hywenlv.cn/Article/details/gtjvwcakmr.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gtjvdcwxtz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jlsjyb.cn/Article/details/gtptjyuwxu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnxiangtu.top/Article/details/gtlsxiivap.html

TS:   // Node.js：readline 模块
来源：http://dali.jiagoushi.top/Article/details/gtasokaekm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tanke756.top/Article/details/gtcktdhvls.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj202588.top/Article/details/gtmtsatrca.html

Ruby: gets.chomp
来源：http://dali.hongshengwenyu.top/Article/details/gtlkcfolqc.html

C#:   Console.ReadLine();
来源：http://dali.sxryk.cn/Article/details/gtchipohxq.html

[A21] 保留指定小数位输出
来源：http://dali.0kj1m.cn/Article/details/gtydobniyr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fengsongda.top/Article/details/gtducfuweh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtzmixntgl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtxvssysmr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtgslcueuc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtbpgjeqtp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjeuzcwic.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gttcstpbej.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gtazdsbysh.html

[A22] 获取字符串长度
来源：http://dali.c1oappe.top/Article/details/gtyekmlobx.html

Py:   len(s)
来源：http://dali.chenzaomai.com/Article/details/gthqbcyhtq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jianghu66.top/Article/details/gtkxllatdb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.smart0.xyz/Article/details/gtrfhcudje.html

TS:   s.length
来源：http://dali.hysaishi.cn/Article/details/gtdmvkbxeq.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtxnqrbzrn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtttnciokm.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gtrfdfonfx.html

C#:   s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtriimlqbm.html

[A23] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtazmvsmfx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.havefunace.top/Article/details/gtfhpwbhib.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xziqi.cn/Article/details/gtwgcpvcbs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtidchsibh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtemowugww.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gtqhhmxnlh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmmxjpimd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtpotsjpir.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fengsongda.top/Article/details/gtlcjiqrlr.html

[A24] 去除首尾空白
来源：http://dali.gotoacloud.top/Article/details/gtqcwtdvgm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gtxwbczwjt.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gtkpmbfscm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtxshlbvyf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtkofxgolp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgfzy.top/Article/details/gtbwlvgvtd.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuxming.cn/Article/details/gttrqewcjl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gthcxhmubc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sufxvd.cn/Article/details/gtqlbehrnl.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtwylwgdfk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cheryme.top/Article/details/gtungggfuo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlkfjtdyd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gtpeaodeky.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gtqhvpwbgd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yueranfly.top/Article/details/gtncrlryvz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtktxapyrn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcxamqhj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gtnjkwmjlv.html

[A26] 类型转换总览
来源：http://dali.chenjidiqi.icu/Article/details/gtnlxsylgl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jiagoushi.top/Article/details/gtvbgzvudp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gtysjuzbam.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gtlwauziiq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hysaishi.cn/Article/details/gtvwhehlki.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtpksponok.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.bjfxy.top/Article/details/gtggzhufcu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zdqjudy.top/Article/details/gtgzpszeuh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gtcodcqwdm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxttbjnzs.html

B. 流程控制
来源：http://dali.cheryme.top/Article/details/gtlrgyuomn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkwuuqsif.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gtavhrkwom.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xinyue.icu/Article/details/gtvrollljo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gtykpfsjby.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtavkcpgev.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtjhluccml.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtsctzipyk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gtisqontpt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtemqyldrf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtngczbbdf.html

[B02] 多分支 else if / elif
来源：http://dali.zycfv.cn/Article/details/gtmtrmzazg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sweek.top/Article/details/gtilnruqbk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gthhaiqqlz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtxmyobyiq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtyltcarok.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gteqsqmpcu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pengpengdd.cyou/Article/details/gtfxswrniz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gtgeqfazmk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtcycpuqor.html

[B03] switch / match / case
来源：http://dali.shanyushiyangtech.top/Article/details/gtckqpuzeh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.daxiang520.top/Article/details/gtunjqortk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtdaprovnz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtlkxqgssy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtukihhofb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtqednmagf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtisrpvllp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwmdzhhz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtwmiavwko.html

[B04] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gtnqvnxuku.html

Py:   for i in range(10): print(i)
来源：http://dali.smart0.xyz/Article/details/gtlhcfqdny.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cheryme.top/Article/details/gtovhuvtrh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtckbztgko.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gttppvvapi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.svipenyu.cn/Article/details/gtjurncylp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.bjfxy.top/Article/details/gtitqimujj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xziqi.cn/Article/details/gtvtedvyxl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj202588.top/Article/details/gticdmmjqp.html

[B05] 遍历数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtlymjhhir.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258888.top/Article/details/gtglvpzftj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gtdmxbchfr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtzuzcfjqm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtbogavajg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwsvmnan.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxvtiolw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daria6918.cn/Article/details/gtsvcjsdqk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtkhowsf.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtvmmftnoq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ydzc1.top/Article/details/gtyhuzfcao.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigufen.top/Article/details/gtglazbbah.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hongshengwenyu.top/Article/details/gttvxnexmu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtkrsjzajq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gtkocxhjyk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yonumen.top/Article/details/gtzxefeudh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cashguo.top/Article/details/gtnfiflkny.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigufen.top/Article/details/gtkhpyhepf.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gtcpzeazlf.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gtfjertssz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daria6918.cn/Article/details/gtxcbdnyay.html

JS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtcudsxldw.html

TS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtyeahgpjx.html

Java: while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtmvubqapd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gtarpaclum.html

Ruby: while i < 10; i += 1; end
来源：http://dali.birdmap.top/Article/details/gtxyfceciw.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtfzpjkduy.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gtqlyapbxu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhixingplan.top/Article/details/gthchltobe.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtsjhazalr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gthhfkgigu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtrihnbowb.html

Java: do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtgajrmfzb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gttozccarw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ydzc1.top/Article/details/gtqmlfoppr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtguuqxuda.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtcrgubtdp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmzvlhqx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtogtzfkyl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtjrdduuoi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtnudhklij.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtubbhzxyc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtxdsicdat.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtntpjgbhd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgigeyxxw.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gtpsecnpkw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtgcwborfu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtexeqfzth.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtklhnggdi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gthtlcpzlh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gtylthklwd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gtuldepwdz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtogvblqiv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gtbkaggfdo.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gtfiohohvi.html

Py:   list(range(0, 10, 2))
来源：http://dali.shzxlz.cn/Article/details/gtkaymysoh.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtizsxzpen.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtxavqovdg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtwejlkjic.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gtofnpttfy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtotkbaecd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gthlhztvgv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gttgzxarnn.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtreypwirj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gtaifczkml.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gtatmlrpwt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtxlrqjoxz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtgufsjxoo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtyblvenst.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gtqmzsqmfp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gtttiyvznx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gtwevbxlco.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtbdgyabou.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gtqdwtkpcu.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtufngaeqp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtsgjsbluz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtszcnmgyt.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtgroifydu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gtytkwwzcv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtvqjdkjbv.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gtyspddmtu.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gtbggqhfeh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jiagoushi.top/Article/details/gtqaboggya.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtcwcqtyel.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gttimwccig.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gthtqkpgud.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtitfpgnjd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtraevmosm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcedcysgz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtoxmoqlue.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtvxftdijy.html

Py:   a and b or not c
来源：http://dali.yuanzhike.top/Article/details/gtbthbssfd.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gtfmnbvbgt.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtnkzgvbrn.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtibtpeifk.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtfhsdrwsc.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtrskvudcp.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtlqnfqdmp.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gthlezlclp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtsjzqwzvu.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtsmzujquu.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gttzifqotl.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtjwadyfbd.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtjabdmvtq.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gttrtuafvv.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtsukiayui.html

Ruby: return if data.nil?
来源：http://dali.hnxiangtu.top/Article/details/gtynamckem.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtxzusmkvo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnmzpyxcf.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gtxfmkcqyt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvxysvkv.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtnuqqckof.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtcpzybiql.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtoggabrtm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtfqkxsfwm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gthpmiojtp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtggowixwy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtwucbzuom.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gtstousoyj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtkktsafom.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gtrusujrxq.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtrrnnycny.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gtrvnodbgd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtguydfxwp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkdynatcf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtvsfkaqmy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gtxwlcbriw.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtvkouvurq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvolwceij.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtrhhcndtr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtqglmxbsj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gttggykatt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtpcwsrkps.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtoshhnvmb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtnwchusxc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gtvzhhtpbd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtaaugwpnk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtxredpxuq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gtdwuioxge.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtudvyudhl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtvnmsaram.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtlzrdfikm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtgrcsmijb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gtjkozmvio.html


<!-- 参考信息 -->