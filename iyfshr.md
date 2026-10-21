代发 wailian999

JS:   x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtybaurlqu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtzibvnvsv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyelawnl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.0kj1m.cn/Article/details/gtspzizbfn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtflpvvhrs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtxxnhxsnh.html

[A12] 字符串插值 / 格式化
来源：http://dali.jyoumei.cn/Article/details/gtufbshksb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj202588.top/Article/details/gtzdvwkjoo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.redwolf501.top/Article/details/gtgfxdifac.html

JS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtdneajskk.html

TS:   `Hello, ${name}!`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdldmykcl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fengsongda.top/Article/details/gtvnnitzdq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gogol.net.cn/Article/details/gtzmqhunkw.html

Ruby: "Hello, #{name}!"
来源：http://dali.zdqjudy.top/Article/details/gtkysebvjo.html

C#:   $"Hello, {name}!"
来源：http://dali.tianlin.xyz/Article/details/gtbwkmtmxb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.fzhhl.top/Article/details/gtgequvwrp.html

Py:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaprhrnm.html

PHP:  "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtfupffjxx.html

JS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtehkbleqo.html

TS:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtsihotkul.html

Java: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtobrrbxyb.html

Go:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtfdntydzh.html

Ruby: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtpmqhvufg.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtchiqofpj.html

[A14] 注释写法
来源：http://dali.nanxinkj.top/Article/details/gtcloljlqk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenlongwang.top/Article/details/gtwdufndfr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtsnvcavjl.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtfqazioix.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtlbckyymc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xuetiantiany.cn/Article/details/gtzzbnewmi.html

Go:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtbztuqtvz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhoulong.xyz/Article/details/gtfyhnokrx.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtkboretyp.html

[A15] 空值判断与默认值
来源：http://dali.hfpthk.cn/Article/details/gturrdngkw.html

Py:   value = data or "默认值"
来源：http://dali.chenzaomai.com/Article/details/gtoevwsygs.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtmfxjrfch.html

JS:   const value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gtehyffgoo.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtoavzcmzw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xuanzx.com/Article/details/gtjpzepjsj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gtimqhtrlp.html

Ruby: value = data || "默认值"
来源：http://dali.daxiang520.top/Article/details/gtnzwwkdfi.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtywdwslfk.html

[A16] 真假值判断规则
来源：http://dali.shuidangran.top/Article/details/gtwtdwolwi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258888.top/Article/details/gtktbzuech.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gzhubu.top/Article/details/gtnkjqqvhg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtuwfcttzo.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gtpykypvww.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cheryme.top/Article/details/gtfvgpgyco.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shangyingyoupin.top/Article/details/gtakftrxll.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gogol.net.cn/Article/details/gtpjmsihed.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.mhx1999.top/Article/details/gtblnwcbfy.html

[A17] 位运算
来源：http://dali.yj202588.top/Article/details/gtzyekjftd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtxhqkgkzi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtvfyyzqbo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtsoedjndy.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtqusbpvuc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtxdyaogbr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtdqgodaad.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtmkvbyzfe.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtpzgsyejs.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gtxbjhaoww.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtrwpnvszd.html

PHP:  ord("A"); chr(65)
来源：http://dali.daxiang520.top/Article/details/gtahwosgzo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtwfqofzhd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gtprbdqjlk.html

Java: (int) 'A'; (char) 65
来源：http://dali.sysykeji.top/Article/details/gthvxjoajk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.pengpengdd.cyou/Article/details/gtuohxdiph.html

Ruby: "A".ord; 65.chr
来源：http://dali.yangfankeji.com/Article/details/gthaokknbe.html

C#:   (int)'A'; (char)65
来源：http://dali.jinghuilouyu.cn/Article/details/gtijlpngxr.html

[A19] 交换两个变量
来源：http://dali.smart0.xyz/Article/details/gtwqjrplct.html

Py:   a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gtdygqkjve.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jyoumei.cn/Article/details/gtzmybncxr.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gteouvguph.html

TS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gtnwfgzqfa.html

Java: int t = a; a = b; b = t;
来源：http://dali.shzxlz.cn/Article/details/gtxooivpox.html

Go:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtgqnnazcp.html

Ruby: a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtoxfditmw.html

C#:   (a, b) = (b, a);
来源：http://dali.chenjidiqi.icu/Article/details/gtzopamwiv.html

[A20] 读取标准输入
来源：http://dali.ppjwa.cn/Article/details/gtsuqvyhvl.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutvsnpxv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.iojbl.cn/Article/details/gtyhlturdv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.iojbl.cn/Article/details/gtdvfzevcn.html

TS:   // Node.js：readline 模块
来源：http://dali.smart0.xyz/Article/details/gtdqikmkve.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtdvuxjxmv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gtvzzcpodt.html

Ruby: gets.chomp
来源：http://dali.guowangkeji.top/Article/details/gtlnemrnbj.html

C#:   Console.ReadLine();
来源：http://dali.hammf.cn/Article/details/gtidzjtqey.html

[A21] 保留指定小数位输出
来源：http://dali.c1oappe.top/Article/details/gtirgsquoo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gtqxotmxxw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtzvkwzgmu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtiqzuxean.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtfsjgkhmw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtuvdfdzwa.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtnpdbdcaj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtxcpfjlcm.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuxming.cn/Article/details/gtpcyxymsq.html

[A22] 获取字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtlvxflnmd.html

Py:   len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtipzbsjrm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hongshengwenyu.top/Article/details/gtikmsniqc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenodhwjo.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gtozhwxnmc.html

Java: s.length()
来源：http://dali.nanxinkj.top/Article/details/gttvrxntgp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gotoacloud.top/Article/details/gtvkyxcpwi.html

Ruby: s.length
来源：http://dali.chenzaomai.com/Article/details/gtiukaoopa.html

C#:   s.Length
来源：http://dali.iojbl.cn/Article/details/gthoblfgfr.html

[A23] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtuuzrbqgw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gtnmyyhyoi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinqigufen.top/Article/details/gtgjtceljo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtkrxqkehl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtvgqiynds.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtcrscktxi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hywenlv.cn/Article/details/gtcvexqyqx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtccnlzxnx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gtxgziknsr.html

[A24] 去除首尾空白
来源：http://dali.sweek.top/Article/details/gtmhuhgvqe.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuanzhike.top/Article/details/gtpvwhrewd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuanzhike.top/Article/details/gtmdpsahkj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtygojmuxu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtnnotmgrt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jiagoushi.top/Article/details/gtlsinigmx.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfivgmdx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gtvwnyfqva.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sweek.top/Article/details/gtfeebwpmy.html

[A25] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gtbtlxkvil.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guannengcc.top/Article/details/gtkxlhmcun.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gtfggychot.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gtqcklgtux.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtwpolkemg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtjmfsbgse.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gttlawksco.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jiagoushi.top/Article/details/gtlsswvmnn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gtgldbrnxg.html

[A26] 类型转换总览
来源：http://dali.9152youxi.cn/Article/details/gtxivxrxkl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.svipenyu.cn/Article/details/gteeyduqri.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gtozcgovaz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenlongwang.top/Article/details/gtbxhfmqsz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gtmtkjdefm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtjtvlnaph.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gtfuefphow.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fengsongda.top/Article/details/gtothauhoc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtiljumsvn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgezykngt.html

B. 流程控制
来源：http://dali.xinyue.icu/Article/details/gtsvgbfzhm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvpoloepn.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gtulrbowkl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dianchejie.cn/Article/details/gtkzhuxque.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xylfe.cn/Article/details/gtkmvrwcck.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtztsjijsy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtpjwpjujq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gttgdnuacg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xinyue.icu/Article/details/gtphbtdaag.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gotoacloud.top/Article/details/gtdjkpnfih.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtaumaxtqg.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gtcdwncwrb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtrebgviaa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbcnpwptf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtgknylmvk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtopetsqnp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtdpfkiwxf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cheryme.top/Article/details/gtkjhkepxg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gzhubu.top/Article/details/gtmztcrqiu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtqjstqqsi.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gtuukzhkhh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gtrtnirxju.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtrapawhfv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtlikpqvng.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtqluhrzir.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtdknkgyre.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkzrgety.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gtnmoggqva.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtysarirnt.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtunzhmgtl.html

Py:   for i in range(10): print(i)
来源：http://dali.daxiang520.top/Article/details/gtfnkgxpfq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfzajeqo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtniwqaljb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gtdchctwyg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigufen.top/Article/details/gtupmxifcd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.iojbl.cn/Article/details/gtlzbibucu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlwtbrxc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258.top/Article/details/gtfwegqjob.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtndhtphxz.html

Py:   for item in arr: print(item)
来源：http://dali.nwbrower.top/Article/details/gtybwtsbed.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guannengcc.top/Article/details/gtaekplkhg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtwmtwwjyq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gtkhcsqkvi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.smart0.xyz/Article/details/gttovhgvim.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gtfozvnnus.html

Ruby: arr.each { |item| puts item }
来源：http://dali.quarkkingdee.top/Article/details/gtrkjcrdfb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gtwcearvps.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gttwpkvilk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.kuanghao11.cn/Article/details/gtamwmftod.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwcmpcnpo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtgxvjfasp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzmzvoyof.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gtdklshrwh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtiqzttkes.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvplvelfd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cqqwz.cn/Article/details/gttxcobgbn.html

[B07] while 循环
来源：http://dali.c1oappe.top/Article/details/gtjtoufvtd.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gttgevabyb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtgtvvhbdh.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtakeuerhu.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtvthdxmmk.html

Java: while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtqcikezav.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gtqqmjjtfk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gtuaokbezu.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtenbugnhy.html

[B08] do-while（至少执行一次）
来源：http://dali.cdnleiting.top/Article/details/gtdxcpwuxg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hysaishi.cn/Article/details/gteabpeykv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gthbndovzf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtvxtrwogt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtrumpbhwz.html

Java: do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gttxxrijpi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtptkqatiy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gtgvdbxzop.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtqcpuzgth.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gtjphuofzo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hywenlv.cn/Article/details/gtdaimslwl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtuvtxcrob.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtslvctxua.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjdlivae.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtibowrfqk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtwmcfbsve.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtawqunszl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtokjflfqr.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gtfmogsubz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gtnhczsslj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtgysndids.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtricwjxmx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtkzhhdnls.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtflcsbnjc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtvddnheyw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gtpqkvqvvc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyjnhuwmu.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gtxzibtyfk.html

Py:   list(range(0, 10, 2))
来源：http://dali.fengsongda.top/Article/details/gtvyfykzlf.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gtudbkfbhw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiaydhro.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtbeeaqzbr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gtfozowlxy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gtaikntbom.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gtzhijaxeu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtnykwslmw.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtxhrwtpud.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hysaishi.cn/Article/details/gtezprhsgc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gtdejxxzzm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtepqexdyr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtexaoxldh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtqgscqbhj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfyjqbww.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gtmxnhdzhb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtbtppugti.html

[B13] 判断是否为数字
来源：http://dali.hammf.cn/Article/details/gtpauofgqy.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtqtimqxim.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdbsreyd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtsdlwavzy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtjuilsyeq.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtdjrsdden.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxinkj.top/Article/details/gtebspfxih.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtykhoookj.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gthdtwjzuw.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtyrvbkfds.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtipxgefsy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtsrkghsvt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrnzfjcn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtpoykkjbb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtvsnhegbm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtwwbvzbbd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtoudtebmf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtfusvhypm.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtibfiwdcg.html

Py:   a and b or not c
来源：http://dali.cheryme.top/Article/details/gttzuezozj.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gtttqujfxi.html

JS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtbsfbabsv.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gthjedbsya.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gttwvuxran.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtutlutduc.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtgmbrrvmq.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtdtjdduab.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gtoxeifzhm.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmoashvj.html

PHP:  if (!$data) { return; }
来源：http://dali.cashguo.top/Article/details/gtmdmszzqi.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtxxyzlevw.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtsdwuwwwt.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtuhgnsqxi.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtctyccrzi.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gtovxjhtom.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtgcrhunrt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtiympsoed.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtayvbmosw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzgcyqcoh.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtsxflbuom.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gtwfgfewhk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtgmbpkrgu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtnonjzykn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtorhkdykk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtcwxhyrnq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtajcrgkfq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtfpkqidgp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtilrmqqzk.html


<!-- 参考信息 -->