代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cheryme.top/Article/details/gtrfwnfyku.html

JS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gtbzytutbk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhongyouzk.top/Article/details/gtqgwcpfvr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fengsongda.top/Article/details/gtyhsffgti.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtmhnkunyt.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkvbnzrb.html

C#:   $"Hello, {name}!"
来源：http://dali.hammf.cn/Article/details/gtgmcfcxqa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hongshengwenyu.top/Article/details/gtkodbplyc.html

Py:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtjulkfsik.html

PHP:  "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gthhaxitgb.html

JS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gttirzotyx.html

TS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gturaftlbx.html

Java: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtigizryzi.html

Go:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtmfergdxf.html

Ruby: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtznumygtn.html

C#:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtnfbcaflw.html

[A14] 注释写法
来源：http://dali.svipenyu.cn/Article/details/gttxuzuchk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangshuangyany.cn/Article/details/gtgudvgbtx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtqzgselsb.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtfizvigwa.html

TS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gtbhvzfjtd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.9152youxi.cn/Article/details/gtechjbybz.html

Go:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtqvpxkxit.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.kuanghao11.cn/Article/details/gtmvwjdlmm.html

C#:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gthtlrplke.html

[A15] 空值判断与默认值
来源：http://dali.cashguo.top/Article/details/gtgtuyrsfj.html

Py:   value = data or "默认值"
来源：http://dali.hammf.cn/Article/details/gtbxwbccnw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtqedyszeg.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtpevjowmg.html

TS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtnrlyndlv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gtbfdomeit.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cashguo.top/Article/details/gtvgylzfyy.html

Ruby: value = data || "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gtkjjtezud.html

C#:   var value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtvrrfabim.html

[A16] 真假值判断规则
来源：http://dali.gotoacloud.top/Article/details/gtjpsceizg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtnqlfguxa.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yvedp.cn/Article/details/gtoecvlagy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guowangkeji.top/Article/details/gtiqdtjuas.html

TS:   if (!x) {}
来源：http://dali.ppjwa.cn/Article/details/gtcrpzddye.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ybcxt.top/Article/details/gtyrhjlisz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gteclgvrow.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhixingplan.top/Article/details/gtziniquny.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgpgisbb.html

[A17] 位运算
来源：http://dali.c1oappe.top/Article/details/gtbzujeisy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtzuzylplo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daxiang520.top/Article/details/gtttilecch.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gthuwvdhrh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtxvcigiwd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtwtxftlht.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtbzelczyy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtgnvpzxcd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtthidxadh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gtajtfvdtl.html

Py:   ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtcokdjvti.html

PHP:  ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gtvtvmysam.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gtboeombpj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtvuaibyzv.html

Java: (int) 'A'; (char) 65
来源：http://dali.gogol.net.cn/Article/details/gtdtzghihv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigufen.top/Article/details/gtalfawmdg.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhengqikj.top/Article/details/gtzqbvpsbs.html

C#:   (int)'A'; (char)65
来源：http://dali.yj20258888.top/Article/details/gtbwvkmxva.html

[A19] 交换两个变量
来源：http://dali.zycfv.cn/Article/details/gtyinugttn.html

Py:   a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfzfuryd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sxryk.cn/Article/details/gtubkngvjz.html

JS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtkafwlcvc.html

TS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtnkeegxnp.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinqigfzy.top/Article/details/gtaxutrfkm.html

Go:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtaiifvcge.html

Ruby: a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtoraijpkq.html

C#:   (a, b) = (b, a);
来源：http://dali.ybcxt.top/Article/details/gtorfdncas.html

[A20] 读取标准输入
来源：http://dali.andypj.xyz/Article/details/gttssrxbwi.html

Py:   name = input("请输入：")
来源：http://dali.sweek.top/Article/details/gtijkduqbh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jyoumei.cn/Article/details/gtbyatjmqe.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jlsjyb.cn/Article/details/gtfclawgiz.html

TS:   // Node.js：readline 模块
来源：http://dali.jiagoushi.top/Article/details/gtvrjtejsd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xinyue.icu/Article/details/gtosjdkkwf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgfzy.top/Article/details/gtajsnzwns.html

Ruby: gets.chomp
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoefcycy.html

C#:   Console.ReadLine();
来源：http://dali.hnxiangtu.top/Article/details/gtchpnzqup.html

[A21] 保留指定小数位输出
来源：http://dali.pycfn.com/Article/details/gtikvurasv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gtopvvuehq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtluwjjuny.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwgbuddro.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtqricdptt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtyrdsaamv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtvfswyqmj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtuajohznf.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvvkggqj.html

[A22] 获取字符串长度
来源：http://dali.jianghu66.top/Article/details/gtwujuaryk.html

Py:   len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlikktkjr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangdashe.top/Article/details/gtccyrnswo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhongyouzk.top/Article/details/gtmnhmllyg.html

TS:   s.length
来源：http://dali.dianchejie.cn/Article/details/gtbskwyukq.html

Java: s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtxcudgnvf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmrifsueg.html

Ruby: s.length
来源：http://dali.xylfe.cn/Article/details/gttqjvqskh.html

C#:   s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtmuslzeyx.html

[A23] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtarpqfvdd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nanxinkj.top/Article/details/gtcfxdgosa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenlongwang.top/Article/details/gtwfdafmjh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gthtzrubrf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsdoohos.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtprhwcouy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnhipbzmr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.birdmap.top/Article/details/gtoflvmqyw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.feifeiyinyue.top/Article/details/gtxjvjuivm.html

[A24] 去除首尾空白
来源：http://dali.tian-w.cn/Article/details/gthhfuioyn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigfzy.top/Article/details/gteispjwnu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhongyouzk.top/Article/details/gtyxlbluas.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcywippx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gtpmehswyn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.iojbl.cn/Article/details/gtvbgzoaia.html

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtoqrmiduz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gtvzfdgtrx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtbvbwyhgq.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtkrtxpelm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.c1oappe.top/Article/details/gtpcxqlkza.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhixingplan.top/Article/details/gtmwtzeiue.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gtixvapmaf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gtgjcmmfrh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sxryk.cn/Article/details/gtnjdwusps.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtmabzoitq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuanzhike.top/Article/details/gtmnfwwoqd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gtybnyrqww.html

[A26] 类型转换总览
来源：http://dali.shzxlz.cn/Article/details/gtqjqxxnkr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yvedp.cn/Article/details/gtyutfimcb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gtfjonbqcg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenjidiqi.icu/Article/details/gtsjvuusqe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavhvbhdy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqspzbztm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guowangkeji.top/Article/details/gtxfgfrcia.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gtydvgtavg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcitxjjs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtseyyfotm.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gtvepatebc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwpjftfgs.html

[B01] 条件判断 if / else
来源：http://dali.zdqjudy.top/Article/details/gtvalsaydk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gtusgoifdp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnqzz.top/Article/details/gtsykktlgx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtsnkqimpr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtuwaimldb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtgtessure.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgufenzy.top/Article/details/gtjisynfqx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkuqqvst.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtxbviijct.html

[B02] 多分支 else if / elif
来源：http://dali.sysykeji.top/Article/details/gtulpgowth.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgufenzy.top/Article/details/gthvcfmzus.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgxegllb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtcoithqtb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtrtskzavg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtkebnejmy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gtceuuucyk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gtuqilurbu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtdytzxwop.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtgpzdllrk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gtsvpivqnm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtlcaaelln.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtkjrrhbch.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtbsungzet.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtsayjblue.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gtpifrqebf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yueranfly.top/Article/details/gtighnmuyb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daxiang520.top/Article/details/gttdhcczmo.html

[B04] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtunpduhnr.html

Py:   for i in range(10): print(i)
来源：http://dali.tian-w.cn/Article/details/gtoltuteve.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gtdovicroz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gtqcnhdrqm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtkawmgbil.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.birdmap.top/Article/details/gtwrnstavm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gtkemgqacw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuanzx.com/Article/details/gtcvejmuwr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gtccbhbtrc.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtijffxium.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gtotadojks.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gtpkzpmqul.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtzmijglcx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtdqkydnvq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenzaomai.com/Article/details/gtvzatmbwj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gtraueasjg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gtobxhqwgv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gtwjywbbww.html

[B06] 遍历字典 / 对象
来源：http://dali.hysaishi.cn/Article/details/gtbsiyxnwj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gtpvvvhvom.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gtjpdnqznx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtnqrzivpi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gtdprazvzg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daria6918.cn/Article/details/gtzpxybixv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtvmvifgii.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gtrrfzfkkw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gttuopqqjq.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtnscuadtf.html

Py:   while i < 10: i += 1
来源：http://dali.daria6918.cn/Article/details/gtrdrrpuxo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gttswnmmwv.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtcxrurosc.html

TS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtmajjhbqg.html

Java: while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtxzgszrpd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj202588.top/Article/details/gtlckrepdo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtdnshgpxa.html

C#:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtsnieriiz.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gtvxxhcfkb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtduidavbr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtieqiuxce.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtctudyfez.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtymkrpvki.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtgpxfxcjg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtjaratyyn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gtarjvlhui.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtylecnrqj.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gtxxmbesjr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gtaqwktaru.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtzmlsuaww.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwubecser.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gthdcipxif.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtfskesrzq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gthyxcwcax.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gthimijdkb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gteybnmxot.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gtdmqxsauv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtmikyvmtu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gtxbscuamj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtetsfcjcf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtgonsnrkk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shuidangran.top/Article/details/gtpuwfvogm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dashuyun.cn/Article/details/gtvcitjnid.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gthdwaemil.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtrhjafzlq.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gtytuuvkrg.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtgclykrns.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gteikufoop.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtekbyehfi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtpexfaafw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmjcaqjgv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtcsaqadnp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtiqtthxdo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gtyforllrs.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gtpdvinbgl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gtmzzusgsg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtswexwpub.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtpruywqbo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtbhvvhemu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtqhdlpngv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gtoxjngyso.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gtnsjqsctn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gtlwjdwqxe.html

[B13] 判断是否为数字
来源：http://dali.xylfe.cn/Article/details/gtnltwsbat.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlzzpyyg.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gthyuuffni.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtdqylmckp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtqchnpzzd.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtotyxxzxd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtnsdcilzs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gtdedgxvia.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gthjvqobox.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gtgmxtjqri.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtqzwillos.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gtvulgjurb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtfgyrfngc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbcagvip.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gttgmvgdzv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gtsjitgeni.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gtnbmbxgqv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gtzpiyktnw.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtbpxfuuoj.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gtuprephys.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gtfgcssysj.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtcgckubnj.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtbpvkgysa.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtxzfyqodx.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbcpqbnm.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gthcuhiqgd.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gthamtsnuv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtkdlazwle.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gtqriqtnqd.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsblqvzkj.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtlnrfzkwz.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtjkrmjvtf.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtlhfcncrz.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrekuocnc.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqgysjqc.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtzeypdiog.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfoiqcrlq.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtepjeluho.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtegylunol.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtchinheou.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtclwzjoqp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtpbwnnvyg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gthvzfnplu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtgjukfrle.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtppevftsy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gtniczcxxr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtioilniyo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gteecsdddd.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gttywlksqr.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtmeykyhdb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gtgiopmmol.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwevuyalo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqguczjux.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gthcplbagt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gtodezpuws.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtbzqqgvln.html


<!-- 参考信息 -->