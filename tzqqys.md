代发 wailian999

[A14] 注释写法
来源：http://dali.snrcjt.cn/Article/details/gtvomzjsrf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hysaishi.cn/Article/details/gtxognrncb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtmkjoqdan.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtsxkkcmsh.html

TS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnsjftns.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xylfe.cn/Article/details/gtrzatkibx.html

Go:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gthqqmljcw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sweek.top/Article/details/gtnezvshbb.html

C#:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtzxeywbuo.html

[A15] 空值判断与默认值
来源：http://dali.xziqi.cn/Article/details/gtqyygpsyb.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gtnbemgmea.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gttcvvqgcm.html

JS:   const value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtaatabsuo.html

TS:   const value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gthraforsx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xinyue.icu/Article/details/gtqocirmni.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrupnzoul.html

Ruby: value = data || "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsqlcjjm.html

C#:   var value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtaixsgllm.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gtxbsfzfbx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcykyssni.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhoulong.xyz/Article/details/gtlktkxfqc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnqzz.top/Article/details/gtltxtvlqc.html

TS:   if (!x) {}
来源：http://dali.jyoumei.cn/Article/details/gtrlimgrsk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbjeikhoa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yueranfly.top/Article/details/gtukqdplpp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigufen.top/Article/details/gtdulksdca.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sxryk.cn/Article/details/gtukmxjfrf.html

[A17] 位运算
来源：http://dali.fzhhl.top/Article/details/gtpjytouym.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtxecsbgtv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.meibo888.top/Article/details/gtbanfcuta.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtgsamscxn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtmnzetmdj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtpgqwlhty.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtykfurhwu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtsyyqvkoc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gthpduwddc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shuidangran.top/Article/details/gtqheqttjo.html

Py:   ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gtcvwkodai.html

PHP:  ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswauoprk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtamzkxuba.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtvwgrsxmz.html

Java: (int) 'A'; (char) 65
来源：http://dali.hysaishi.cn/Article/details/gtbmezhqlq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daria6918.cn/Article/details/gthjqioxbz.html

Ruby: "A".ord; 65.chr
来源：http://dali.sufxvd.cn/Article/details/gtutloymml.html

C#:   (int)'A'; (char)65
来源：http://dali.chenzaomai.com/Article/details/gtydxevgdm.html

[A19] 交换两个变量
来源：http://dali.nanxinkj.top/Article/details/gttqkdcvys.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtgczcrsol.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gtcsrpfnbh.html

JS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtzojrywbv.html

TS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtkjyowwlw.html

Java: int t = a; a = b; b = t;
来源：http://dali.zdqjudy.top/Article/details/gthrpwqlni.html

Go:   a, b = b, a
来源：http://dali.hammf.cn/Article/details/gtkbihhahh.html

Ruby: a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gttspwavtt.html

C#:   (a, b) = (b, a);
来源：http://dali.pengpengdd.cyou/Article/details/gtjwhttguv.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gtqzzidxef.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvjcjefg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhiwuduotai.top/Article/details/gtnukcavwy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.meibo888.top/Article/details/gtjvbtgkua.html

TS:   // Node.js：readline 模块
来源：http://dali.jyoumei.cn/Article/details/gtjqumqyaq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xinyue.icu/Article/details/gtaonrhcnp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sxryk.cn/Article/details/gtcrdxayjr.html

Ruby: gets.chomp
来源：http://dali.yongpay.top/Article/details/gtxkugxnub.html

C#:   Console.ReadLine();
来源：http://dali.yj20258.top/Article/details/gtjidtvrdr.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasuadjsx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhniwdir.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtixxhfzwf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtiikacqib.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtqwxmljyo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtxunmegaq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtyamknbcm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gthpcomkgs.html

C#:   3.14159.ToString("F2")
来源：http://dali.gzhubu.top/Article/details/gtvvtjwdup.html

[A22] 获取字符串长度
来源：http://dali.fengsongda.top/Article/details/gtylbvaljp.html

Py:   len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyprwofbq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gteajjovmf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258.top/Article/details/gtjtkaaluy.html

TS:   s.length
来源：http://dali.smart0.xyz/Article/details/gtocmscbfo.html

Java: s.length()
来源：http://dali.dianchejie.cn/Article/details/gtqrrjiwrc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtxitsurvr.html

Ruby: s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtpuwtpjei.html

C#:   s.Length
来源：http://dali.316326.xyz/Article/details/gtuskntqnp.html

[A23] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplzmswua.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xinyue.icu/Article/details/gtkftljnqp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yvedp.cn/Article/details/gteefvhmfx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtnuipsomk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqgzjkag.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtornipbfk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xziqi.cn/Article/details/gtjlcueyjq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtimnrldkl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shzxlz.cn/Article/details/gtsgrbuedz.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gtcmukvewc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgfzy.top/Article/details/gtegiwgeem.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ivvv.top/Article/details/gtiwijlshu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtqfwlkmrr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtzlcdrzjg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yangfankeji.com/Article/details/gtednrungb.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuxming.cn/Article/details/gtlouoiqkr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daria6918.cn/Article/details/gtyaycdkba.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.iojbl.cn/Article/details/gtluqcffiy.html

[A25] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtpmyiyxlf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ehwqpu.com/Article/details/gthaigwiln.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yvedp.cn/Article/details/gtsngepmst.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtqjcvlick.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtcltpygbd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ydzc1.top/Article/details/gtfmluqjub.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtgtakpkrm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gtbtjveydd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtrtiexttz.html

[A26] 类型转换总览
来源：http://dali.fengsongda.top/Article/details/gtsuovmmnr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtbjnmejzo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gtenpoopzm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xylfe.cn/Article/details/gtmcnnmhco.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenlongwang.top/Article/details/gtwmueyfks.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtqanunlsn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.haohaochexian.top/Article/details/gthqswjzxf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yueranfly.top/Article/details/gtnbycrpda.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtlvxxnkbh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmyiyoaue.html

B. 流程控制
来源：http://dali.c1oappe.top/Article/details/gtetqybpsm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtoefgvlae.html

[B01] 条件判断 if / else
来源：http://dali.jlsjyb.cn/Article/details/gtydhvdcmu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gtrqywqaco.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ydzc1.top/Article/details/gtlfgljozj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtvwpnpcvm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gthrqijrnf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtsvjdwelz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtcthszgwk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dashuyun.cn/Article/details/gtrsjpfazq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtqmvjpvgk.html

[B02] 多分支 else if / elif
来源：http://dali.hysaishi.cn/Article/details/gtmejhcenx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiumnrorp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtosidjxgk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtacpqbhjl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtqfrxvsqz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtltlkfkho.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gtaxazwlsf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gtarfejccz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtuhszbyux.html

[B03] switch / match / case
来源：http://dali.zhengqikj.top/Article/details/gtndxjuknc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gtzjyjkqap.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtyjuvyimx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtltovkhcg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtuidfrlrt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtvhizexyk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.c1oappe.top/Article/details/gtnipiqgpe.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeqzkrxy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtmpucgsoo.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtqamhtcyg.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gtaabsdnfm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.vqdsnc.cn/Article/details/gtooavzvtr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtzgrzlzzh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gttowodzli.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.0kj1m.cn/Article/details/gtqtxzflcy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.vqdsnc.cn/Article/details/gtxdzfflxf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gtygdppngx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenzaomai.com/Article/details/gtiefhejmj.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gthlroqhjb.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gtgbkmvpho.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hfpthk.cn/Article/details/gtncgsoqwz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtiaclxyzc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtaoagxmqf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtoacyjbhz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gtywxtjkop.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtckqjoveb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gtxdwiqnge.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gtlejibxnm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuanzx.com/Article/details/gtomnzfbqu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhixingplan.top/Article/details/gtzivptrot.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gtpuyeepea.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gtukqchylu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gtlgdqriuw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gtqercwkyh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gtgbqyrppg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gtnqozrggx.html

[B07] while 循环
来源：http://dali.jlsjyb.cn/Article/details/gtlcjsizwn.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gtedgwdwkd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiwzvrxun.html

JS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtmdymqhjs.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtmmmbyesi.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gttrqbwzvz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cdnleiting.top/Article/details/gtohhzsueq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsuxihib.html

C#:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtnfmidkqy.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gtqkjqfida.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gtwuwyppbq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtvnmofswe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtkludwuzd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtlxghzdvo.html

Java: do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtkxmeypih.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtuvyqgykp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtjonotbof.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtyttyacgi.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtfpjgorhb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenlongwang.top/Article/details/gtpqioqozx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtfofhiaiu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtsvbsapfc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gttqqiinkq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtitpfwecs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gtyeonymjh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtoldplknu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtdxvcjdgm.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigfzy.top/Article/details/gtcijhmdmk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtzbvydled.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yonumen.top/Article/details/gtjvwfbnhc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtlvznxdle.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gtpxeznywj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtrxtthury.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtizvnqemw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenjidiqi.icu/Article/details/gtzsyxhths.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gtuaawydqx.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmieumog.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuetiantiany.cn/Article/details/gtulncmgfj.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtaeekjakc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtmzusignh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtewhmamec.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtwadhmghg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gtoyfpwjlc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdyhpfah.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtribjypdb.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnusmdivn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtvscfhymv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtvxnuckzw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtikjwvfpd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtkpqwhmxf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtalhmlqqe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gttmagijnt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gteqylxpmo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gtfsidoqsu.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gtoikkmexu.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gtubxhggkp.html

PHP:  is_numeric($x)
来源：http://dali.ivvv.top/Article/details/gtvzqxdfwv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtfufolhug.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtavysbggj.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gtzgsffkbk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gttzxixnud.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gtqhbrosho.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gtioxibzxr.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gtkxwodelm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtsrvljmer.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jyoumei.cn/Article/details/gtupbiroqj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjpnmphow.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtwztpydpr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtfgrjdcuv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gtynstrbyk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtuehvoirt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtsxptfmce.html

[B15] 布尔运算与取反
来源：http://dali.yj20258.top/Article/details/gtdzatbbht.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gtrvmmecaz.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtxydafxjh.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtryhgkgtq.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtshuympqw.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtnonxtsrb.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtfgqthynm.html

Ruby: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtrbnmrpdw.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtoxhyymou.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtiofzsslu.html

Py:   if not data: return
来源：http://dali.ybcxt.top/Article/details/gtxhnkzipl.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtpmqocnvr.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtbrdoniwh.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtteduirwb.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtqmvtiuyf.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gtftjzucmo.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtpjbunymj.html

C#:   if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtyeepguqr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnoktwrbc.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtutycwhog.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgeckqskl.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gthejthszs.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtmyhnhjsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtzhhayuwx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtgygvrjtk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtopeibkqo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtewvmiuad.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtcesopeay.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstmsgheb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtjdvuxzkk.html

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gtrkrldokk.html

Py:   def greet(name="World"): return name
来源：http://dali.sweek.top/Article/details/gtpuwmzmvs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtgzkhzpnt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtdhmwkdik.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtzrwxmkuo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pycfn.com/Article/details/gtntivhaka.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtbkczxofz.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtdartozgv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtylwisezs.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtwtihitkq.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gttbflfmhs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtyhhooaqr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtqirrdoja.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gttntmbodl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmibohtot.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtcmnfrqsn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxinkj.top/Article/details/gthrxhncnm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gttnzyruup.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtegiziicz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdjvrzdjl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtonbpvuei.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtfhhgnlsd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtkbkhomdw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtmqkdihig.html


<!-- 参考信息 -->