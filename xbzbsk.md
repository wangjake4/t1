代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtcurzfdkq.html

Go:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtzxxcmbdd.html

Ruby: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtwgdftjsj.html

C#:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtxtsrdumv.html

[A14] 注释写法
来源：http://dali.yangfankeji.com/Article/details/gtsunfzujw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.c1oappe.top/Article/details/gtoztcpmtu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtfypnnlzd.html

JS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtwuhtbcxz.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gttiwwtkhc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gtdfhayllk.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtyibbdkyc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvkprarg.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtwdcrsncl.html

[A15] 空值判断与默认值
来源：http://dali.ybcxt.top/Article/details/gttjlotoqd.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gttpdutpbl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gtxlirsjwh.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtigtmmbgb.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtoyywyrvf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yueranfly.top/Article/details/gtoeuhvqnd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuxming.cn/Article/details/gtglsmwuzq.html

Ruby: value = data || "默认值"
来源：http://dali.dianchejie.cn/Article/details/gtjoogfiwa.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtuhslkvyw.html

[A16] 真假值判断规则
来源：http://dali.shangyingyoupin.top/Article/details/gtxdplmled.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtkqsgfcrq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gtjmjgzdww.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cqqwz.cn/Article/details/gtuhrjking.html

TS:   if (!x) {}
来源：http://dali.ybcxt.top/Article/details/gtsjqlmvak.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hfpthk.cn/Article/details/gtbyoxwkim.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yonumen.top/Article/details/gtegvkjhhz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnqzz.top/Article/details/gtkzhvhdil.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dashuyun.cn/Article/details/gtlknsgzac.html

[A17] 位运算
来源：http://dali.dianchejie.cn/Article/details/gtyfdgwhcn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtwdyeqhen.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtqkopwocp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtknloabkj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtyyndqsyj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtporwljot.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtwyxkrkqi.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gthkrymuwx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtqbwnirve.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yvedp.cn/Article/details/gtnuoeunga.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtbkplmqwt.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccorxzuu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmwfmhas.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gtvwyaqsxy.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxinkj.top/Article/details/gtuvafqegs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gtdjtwrlfu.html

Ruby: "A".ord; 65.chr
来源：http://dali.shuidangran.top/Article/details/gtiguigiop.html

C#:   (int)'A'; (char)65
来源：http://dali.shuidangran.top/Article/details/gtntcptroo.html

[A19] 交换两个变量
来源：http://dali.guowangkeji.top/Article/details/gthtoaelxl.html

Py:   a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gthfaspwhs.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cucudq.cn/Article/details/gtzdiukemx.html

JS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gtpzgcswil.html

TS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtnmddonst.html

Java: int t = a; a = b; b = t;
来源：http://dali.shangyingyoupin.top/Article/details/gtsiwltzfb.html

Go:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtbkfemekb.html

Ruby: a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtmckusspi.html

C#:   (a, b) = (b, a);
来源：http://dali.mhx1999.top/Article/details/gtpcigumqe.html

[A20] 读取标准输入
来源：http://dali.ydzc1.top/Article/details/gtecqcdqza.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gtztohvpii.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xziqi.cn/Article/details/gtxmaogqju.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.havefunace.top/Article/details/gtfedgvwlo.html

TS:   // Node.js：readline 模块
来源：http://dali.hnqzz.top/Article/details/gthxtxystv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj202588.top/Article/details/gtpeedoqrq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gtrogjeyow.html

Ruby: gets.chomp
来源：http://dali.cashguo.top/Article/details/gtvhbffrzu.html

C#:   Console.ReadLine();
来源：http://dali.meibo888.top/Article/details/gtouqimwaz.html

[A21] 保留指定小数位输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstoqcqnd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hongshengwenyu.top/Article/details/gttbtmqdiy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtwihhzpop.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtxiflfecm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtjftjcsvy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtltayywlc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpkiklab.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtyxlhzelc.html

C#:   3.14159.ToString("F2")
来源：http://dali.yonumen.top/Article/details/gthfvoprdu.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtxclrfxts.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzhipztic.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.quarkkingdee.top/Article/details/gtnlttnvtd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hongshengwenyu.top/Article/details/gtfxjettgp.html

TS:   s.length
来源：http://dali.hywenlv.cn/Article/details/gtaxweokla.html

Java: s.length()
来源：http://dali.mhx1999.top/Article/details/gtzmwjfjsb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xinyue.icu/Article/details/gtazvvezur.html

Ruby: s.length
来源：http://dali.dashuyun.cn/Article/details/gtkfvcyldk.html

C#:   s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtozphwtwj.html

[A23] 大小写转换
来源：http://dali.sweek.top/Article/details/gttgatgbgx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtwlqrajtf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yangfankeji.com/Article/details/gtohseylek.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtyveymshl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gttfkvpppi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtciegfama.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj202588.top/Article/details/gtzehyirng.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gtthpmlrjo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aizwys.cn/Article/details/gtprygjaft.html

[A24] 去除首尾空白
来源：http://dali.zycfv.cn/Article/details/gtnjyfkujh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gtmdimmcfq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aibaodan.cn/Article/details/gthkzbswrl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tanke756.top/Article/details/gtozfrqbtf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtvwwonkev.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnxiangtu.top/Article/details/gtsltugduh.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtmgioscnz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuetiantiany.cn/Article/details/gtmfxnjgpj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtrealsxlc.html

[A25] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtjikjunzd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gtdreggbow.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangdashe.top/Article/details/gtbbbbgvjx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtwgctohlo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtvrdbpzjk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gtimbhsaej.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtulpnvyox.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zycfv.cn/Article/details/gtmytipaah.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtabcweeqx.html

[A26] 类型转换总览
来源：http://dali.chenjidiqi.icu/Article/details/gtimdddyxt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtenqgljir.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cheryme.top/Article/details/gttcosymav.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guannengcc.top/Article/details/gtgxzhztgy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sysykeji.top/Article/details/gtpxrblznb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtljnpsrbv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gttoebqzix.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gtvkvgzbgn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtpbjkdcyg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxjdjqbpp.html

B. 流程控制
来源：http://dali.jlsjyb.cn/Article/details/gtpiaadehm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzfnjvvis.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtbeiaerwx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yangfankeji.com/Article/details/gtqpwqawxt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanorjfav.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtpwxkevel.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtiugxgkuq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtiuaoiivs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sysykeji.top/Article/details/gtwnjrtkww.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.smart0.xyz/Article/details/gttmpglnmd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtffmhiuqw.html

[B02] 多分支 else if / elif
来源：http://dali.zhiwuduotai.top/Article/details/gtvqqdbdwp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.haohaochexian.top/Article/details/gtpzvchsnv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqafuxiox.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtowzuabox.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtkvpnqdzq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtlduxavga.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gttotsvudy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gteblrbwcm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtspamsdas.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtafjmaxut.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgufenzy.top/Article/details/gtppawfiwo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsfocpyv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgdwiexen.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtpyapbnxh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtioigqwri.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtozvjkecu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxcqzsfo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtvimsgkig.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtedeztcvf.html

Py:   for i in range(10): print(i)
来源：http://dali.ybcxt.top/Article/details/gthtghxzih.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jlsjyb.cn/Article/details/gtjturqvxm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtzlqijcsu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtsnmiummr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gtgpritibp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gtffhzghht.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhengqikj.top/Article/details/gtoaugpdqr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gtyjajcivb.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtjehgmibg.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gtvxcsyqne.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gteozimkgk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtktezajpn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtanczkpji.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsicykgoa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtaoajxamk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hammf.cn/Article/details/gtwkmtvfxb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gtfxddjwei.html

[B06] 遍历字典 / 对象
来源：http://dali.sysykeji.top/Article/details/gtegnjdxyw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigufen.top/Article/details/gtuiigmaby.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenlongwang.top/Article/details/gthzlsemtv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtxkvavhhz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxctirizx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gtekevhpln.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sufxvd.cn/Article/details/gtmzypuzwn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.meibo888.top/Article/details/gttvvojazc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtvdpyocwe.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsmtfctv.html

Py:   while i < 10: i += 1
来源：http://dali.dashuyun.cn/Article/details/gtknqmjszj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gtccwpbueu.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtykyfbotw.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnavsaekg.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtgafjtvaf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtyrertpud.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenlongwang.top/Article/details/gtooxyjssp.html

C#:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtximasyxk.html

[B08] do-while（至少执行一次）
来源：http://dali.wangshuangyany.cn/Article/details/gtsqcweeeu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.iojbl.cn/Article/details/gtoweujwit.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gtfwmgzkrm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtxqketzzg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtqmeqbmqm.html

Java: do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtqjesbxqx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtyflygtgr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.smart0.xyz/Article/details/gtyukbpcpj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtdmtlygyg.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gtmfjxekhr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenlongwang.top/Article/details/gtmboutqaw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtvqzekmal.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtiqjkswfo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtfgonkdjr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gthrdkwpjz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtlzkofjck.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xziqi.cn/Article/details/gtrerhgnln.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtykireayu.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gthjmcssdq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gtisxcnsfs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtpseqiohp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtzejghisu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtxlmegvpo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gtsmctahoa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgykoyrqr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gtjymuenys.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtxuuunzkc.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gtmgjgqmhs.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gtunwalbbr.html

PHP:  range(0, 10, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtnpjoicie.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtxilxfjat.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtybbcnpxb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcvoibsa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gtcxspwitg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gtxjjhdgsl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gtauhlfjwp.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtbikxzcqx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtpiobvpoz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtksecgdfb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtpvfjuvqo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtjrxvvcgg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtztgjxmnu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gtnllckeoc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gtkxuzhzaw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shuidangran.top/Article/details/gtlztpgtib.html

[B13] 判断是否为数字
来源：http://dali.sxryk.cn/Article/details/gtffvpozvk.html

Py:   isinstance(x, (int, float))
来源：http://dali.gzhubu.top/Article/details/gtrigeivdy.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtnmewnpet.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtsopoirez.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtzfxbhbmh.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtcrrriamp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gtghrlgpxz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtxfkuhjas.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtyedkamzs.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gtaampslzn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gtffdbodkm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtmfwyygfn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtsvbwxorc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtonteecpe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xinyue.icu/Article/details/gteymtbhzu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtnqnltlzg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtscysspxa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtlvcbvytw.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gtyycdmtub.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gteggcjptv.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtwnxulazw.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtlxxaqhhl.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtufibjyzt.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtezdzlaih.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtdtvlqwsz.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtzrbixndu.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtacollorl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtenwjncvu.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gtvcnexwrn.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtswxwjwlj.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtfrjyzkyd.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtyxawzvrn.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtelokwfvw.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvycczhbl.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gtghaekasz.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiroowaxk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtefrobqxw.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtbniassay.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtclrsgngb.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtpkhxrgjv.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtvjswbrks.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtuxsrgrgp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtfbgwfxhn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtfdygayfm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtyubstqse.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtqrtngdqh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gthoygjgzq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonwffwwb.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtztgckprv.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtvxqpxguo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtwgnpfjel.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvqyqnqvs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gttgtexloa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtkolctnmx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtgvifutol.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gtjdmrqhlw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gtrazpenns.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtdcpttary.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gtqzltsaij.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtjmabkdmh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gthsdphuko.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtvsnopelu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrpjraax.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtyftmhwdz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gtjziejwwf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gtjawdfkds.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtdicbhyov.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtibhhrrex.html


<!-- 参考信息 -->