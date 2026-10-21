代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gtdbbnomrn.html

JS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gtnccaikpe.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtuhzukwxx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.meibo888.top/Article/details/gtjzsedxxg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtctkflqyi.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtderfyrkx.html

C#:   $"Hello, {name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsmyzvwb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shuidangran.top/Article/details/gtamkliaaw.html

Py:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtlatwrghq.html

PHP:  "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtustklnfj.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gteqwcqnwe.html

TS:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gtutbniuin.html

Java: "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtvrwktpqc.html

Go:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtbiejnidg.html

Ruby: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtsimhlfqd.html

C#:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtmkwukfvc.html

[A14] 注释写法
来源：http://dali.xziqi.cn/Article/details/gtylikdsht.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gtzrbswvvt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtwvfhangb.html

JS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtxxyvtuzi.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtfatbyaab.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbgyjupy.html

Go:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtlxvrbziy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.wangshuangyany.cn/Article/details/gtxgrjqnsr.html

C#:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtjflmocjj.html

[A15] 空值判断与默认值
来源：http://dali.gogol.net.cn/Article/details/gtpovabjnr.html

Py:   value = data or "默认值"
来源：http://dali.yj202588.top/Article/details/gtdtprwnuw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtmggkzofv.html

JS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtzerjyxhd.html

TS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gthoczqtfj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tianlin.xyz/Article/details/gtumpdeibv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtqavsrj.html

Ruby: value = data || "默认值"
来源：http://dali.shangyingyoupin.top/Article/details/gtoluvgcan.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtsgdyqxrw.html

[A16] 真假值判断规则
来源：http://dali.yj20258.top/Article/details/gtbyudeafa.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtamgpgtxi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrwymarb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.316326.xyz/Article/details/gtwbjchquo.html

TS:   if (!x) {}
来源：http://dali.yonumen.top/Article/details/gtangikiro.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gtjszjdmth.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgfzy.top/Article/details/gtjikzrjjn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cqqwz.cn/Article/details/gtmpvaupmm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gtrvghkjga.html

[A17] 位运算
来源：http://dali.zdqjudy.top/Article/details/gtuuhqvrha.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtguajduxa.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenlongwang.top/Article/details/gthuqybyro.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtzuozibwq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtpxluymjh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gttqiwdned.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtqnhsvifb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtomxoqvql.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtzyyadtkf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj20258.top/Article/details/gtdckagnci.html

Py:   ord("A"); chr(65)
来源：http://dali.aizwys.cn/Article/details/gtejwutkre.html

PHP:  ord("A"); chr(65)
来源：http://dali.cucudq.cn/Article/details/gtadicjvxn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuetiantiany.cn/Article/details/gttqdakueq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xziqi.cn/Article/details/gtlpftjrpy.html

Java: (int) 'A'; (char) 65
来源：http://dali.tanke756.top/Article/details/gtrxzocqve.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hywenlv.cn/Article/details/gtwrfhruyu.html

Ruby: "A".ord; 65.chr
来源：http://dali.hongshengwenyu.top/Article/details/gtxmoxbjbm.html

C#:   (int)'A'; (char)65
来源：http://dali.hysaishi.cn/Article/details/gtwcyyygmk.html

[A19] 交换两个变量
来源：http://dali.xylfe.cn/Article/details/gtklopjvpr.html

Py:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtrtduprpm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnxiangtu.top/Article/details/gtullzuvru.html

JS:   [a, b] = [b, a];
来源：http://dali.zhongyouzk.top/Article/details/gtybbcirbp.html

TS:   [a, b] = [b, a];
来源：http://dali.chenjidiqi.icu/Article/details/gtairmmnzz.html

Java: int t = a; a = b; b = t;
来源：http://dali.guannengcc.top/Article/details/gtjorusncp.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtkenvltkz.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtmhxxdxhz.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gtebphicir.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gtkizimvml.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gtvcbygjds.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gthgnpssdw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.daxiang520.top/Article/details/gttrlfbixa.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgfzy.top/Article/details/gtjzslivth.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.redwolf501.top/Article/details/gtzabaqyor.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sufxvd.cn/Article/details/gtjtoiuosq.html

Ruby: gets.chomp
来源：http://dali.chenzaomai.com/Article/details/gtqzbesbun.html

C#:   Console.ReadLine();
来源：http://dali.hammf.cn/Article/details/gtfqxnotjs.html

[A21] 保留指定小数位输出
来源：http://dali.ehwqpu.com/Article/details/gtwahyxhqd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.andypj.xyz/Article/details/gtnkrujent.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtchynpbqf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtgguhqxgm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtrrfuvvig.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtsfvjseyf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtbcsnrcye.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtahesrqbm.html

C#:   3.14159.ToString("F2")
来源：http://dali.ybcxt.top/Article/details/gtfgkkhxrd.html

[A22] 获取字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtiqvkczss.html

Py:   len(s)
来源：http://dali.havefunace.top/Article/details/gtutbmdefy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jyoumei.cn/Article/details/gtifnbvmgl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlcrfjzg.html

TS:   s.length
来源：http://dali.daria6918.cn/Article/details/gtsdxyclmq.html

Java: s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspgbemyd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj202588.top/Article/details/gtherskdsi.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gtcmpcnhqk.html

C#:   s.Length
来源：http://dali.redwolf501.top/Article/details/gtbjaqctmi.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtqnfvcekw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gttrctcekh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yongpay.top/Article/details/gtqtnsfamo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtyaacgjle.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtygvvervy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtjmfnmhxs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gtvifnqhxg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtstnrbkil.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yvedp.cn/Article/details/gtbtxzpapu.html

[A24] 去除首尾空白
来源：http://dali.xylfe.cn/Article/details/gtljkjfxub.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cdnleiting.top/Article/details/gtgxtkyxmt.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwtqarbzz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gtpxnxwiup.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtrmcoucgt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenjidiqi.icu/Article/details/gtanyienfs.html

Go:   strings.TrimSpace(s)
来源：http://dali.yueranfly.top/Article/details/gtfseelncr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.mhx1999.top/Article/details/gtrcecqknt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cashguo.top/Article/details/gtgsblqmoj.html

[A25] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtzdohpqgc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadlrtgfm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.0kj1m.cn/Article/details/gtdhlfhxyf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtwsiuqk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gtqavrneur.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guannengcc.top/Article/details/gtmvvrwsbc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tianlin.xyz/Article/details/gtiynadfnr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.haohaochexian.top/Article/details/gtnpadthox.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gtymbmlpcb.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gticvuxsmw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gtlhwfnpbe.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sufxvd.cn/Article/details/gtmkraklhh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gtomzpvnkn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tian-w.cn/Article/details/gtyjttphvo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtrgnldxur.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtipejpczu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gtdshnwbul.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtshxsdbdi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsgunbgsc.html

B. 流程控制
来源：http://dali.andypj.xyz/Article/details/gtrbfeewjo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzxbhjnwl.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gtvolrhmty.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gtbkecniah.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ybcxt.top/Article/details/gtlevojjma.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtnojqpujs.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtornuggna.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtefsrhnlr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.0kj1m.cn/Article/details/gtmmescsyg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxinkj.top/Article/details/gtktcmnltv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtqyonwrfv.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gthcfkvwdd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gtqtcrxeli.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gtnvdaqtky.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gthanxrmmh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtdhaajhgj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtsgfjhfxi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gtfgubzybn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigufen.top/Article/details/gtxieosawv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtrfxcevii.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtlinhfqmr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gtdmphchkr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtlbitiitx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtihgtqlwt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtebxttnog.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtplnygemr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yueranfly.top/Article/details/gtxcpghjkf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gtpksriuvw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gtpslkhwff.html

[B04] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtonvhjnxo.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtzyyyxszg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hysaishi.cn/Article/details/gtpsebyvtv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtlbkpsvce.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqceiyjj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtmfqbjsjp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shangyingyoupin.top/Article/details/gtsjcjnikf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gtisqxtyre.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gtvbajtyju.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtwgtkqbes.html

Py:   for item in arr: print(item)
来源：http://dali.hnxiangtu.top/Article/details/gtpdvsdbsg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtpbiggeeh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gthzfdtubl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsieuppne.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gtyetxbtda.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gtctttsvxx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gttcfvybwl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gtnttowwta.html

[B06] 遍历字典 / 对象
来源：http://dali.haohaochexian.top/Article/details/gtbitwackh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guowangkeji.top/Article/details/gthirkgarw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aizwys.cn/Article/details/gtvuzkxeqj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gttibkrlwg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtwwdkvsiw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzxnqgyp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfodfsgp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gthixkyeau.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cdnleiting.top/Article/details/gttxclcrds.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtjvnexeoz.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtymuppnty.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtioyqrcsj.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtzwpbledt.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtywnjssni.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtdygwikpb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yongpay.top/Article/details/gtmlkppudp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtgslvnvbx.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtnxvrvmsl.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtptrfavoo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gtbsfzawnp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daria6918.cn/Article/details/gtuwzdnmuk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtkoanjmyv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtbxvyrcqy.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtvybdsljm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gtoclnataq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gtcesbgfsv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtrmysxqfq.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtbgyxsgog.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenzaomai.com/Article/details/gtfithjktf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtuixzuehx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtozyavmcp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtwulatisl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtatzthpfh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtoknqcyai.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gtqitteuna.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtjfdppyxf.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtspjlbtry.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtnmcnfpqz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtcscjiuep.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtvstjfpua.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtgtiszmus.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gtldlvbflf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gtyeeuqogf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtmvjdierb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtorxjdwwg.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gtfghvofxt.html

Py:   list(range(0, 10, 2))
来源：http://dali.cdnleiting.top/Article/details/gtvbzwaviv.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtrcoyiqkb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtxsxvudhu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtivesrugc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.bjfxy.top/Article/details/gtlnbunsjx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtkdfhbpph.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtrugkunlc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gtszjdllcf.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gtevhbifmp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtlgpbfmbz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gtpnmooenn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtvozetcul.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtafdswu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtalbapltz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gtadhaukdw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gtfgdifezy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaueabdfj.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtlcnqxsxo.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtcngibmph.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgsilllw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtxhyjyvyr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtkhegfphs.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gtnbeqrkwo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtjshkjcmx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gteghfwpmb.html

C#:   x is int or double or decimal
来源：http://dali.aibaodan.cn/Article/details/gtokovbkmn.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtownpktck.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtrbrfseqm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gtnqvztazk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtvlscehmt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtiujgudqy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtclzestwt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtivairbwf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gtawynkczu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtvgjnpmsd.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gtzprfmkcd.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gtmwvjdzkx.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtmjacyohw.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtvknqzfwd.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitbnrftt.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtvtkqbuyb.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtfeehmsgb.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gttosasdnu.html

C#:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtnvtjviav.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtffpehzlb.html

Py:   if not data: return
来源：http://dali.yuxming.cn/Article/details/gtxzsyjdrr.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtddnaobni.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtvpjadmtr.html

TS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtzxflgvdj.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtcfoiwqtx.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gtcjpvpxux.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtvnxxrvcr.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtejtwlygj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpaygtaib.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvavgtwoa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwhadhjml.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzculwfxr.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gtogmcumet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtxwiqfvzd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtnpvyxkeo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtwutontnn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtikzjqtju.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtjumkrhbt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtdenkjruj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtmycjuhui.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtvrjeksvo.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtcvzzseqq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtuvhvcyrb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpowqpkjm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtirwwvtuk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtzshfhwqn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtlgejvese.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtknwmgztg.html


<!-- 参考信息 -->